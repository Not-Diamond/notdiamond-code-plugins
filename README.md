# Not Diamond Code plugins

Plugin marketplaces for Claude Desktop running on Not Diamond Code. `notdiamond desktop setup` adds both.

Every connector points at the vendor's own MCP server. Sign-in happens with the vendor, and this repository holds no credentials.

## Default connectors

The `notdiamond` marketplace at the repository root holds one plugin, `connectors`, which Claude Desktop installs automatically. It lists Linear, Notion, Atlassian, Sentry, Intercom, PostHog, Stripe, Attio, Supabase, Netlify, ClickUp, Miro, Hugging Face and Postman under Customize → Connectors.

## More connectors

The `notdiamond-connectors` marketplace under `catalog/` holds one plugin per connector, 124 in all. They are offered under Customize → Plugins → Discover, and each one you install adds its connector. 35 of them need no sign-in and work as soon as they are installed.

## Signing in

Open Customize from Cowork to connect a connector. The Connect button is disabled when Customize is opened from the Code tab, and a connector signed in from Cowork is not signed in for Code tab sessions. For the Code tab, add the server to Claude Code with `claude mcp add` and sign in from a terminal.

## Which connectors are listed

A connector that needs sign-in is listed when its server lets Claude Desktop register itself for sign-in, accepts the callback address Claude Desktop uses for plugin connectors, and returns the vendor's sign-in page. A listing does not guarantee that the vendor completes the sign-in. A connector that needs no sign-in is listed when its server returns its tools to an unauthenticated request.
