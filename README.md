# Not Diamond Code plugins

Plugin marketplaces for Claude Desktop running on Not Diamond Code. `notdiamond desktop setup` adds both.

Every connector points at the vendor's own MCP server. Sign-in happens with the vendor, and this repository holds no credentials.

## Default connectors

The `notdiamond` marketplace at the repository root holds one plugin, `connectors`, which Claude Desktop installs automatically. It lists Linear, Notion, Atlassian, Sentry, Intercom, PostHog, Stripe, Attio, Supabase, Netlify, ClickUp, Miro, Hugging Face and Postman under Customize → Connectors.

## More connectors

The `notdiamond-connectors` marketplace under `catalog/` holds one plugin per connector, 89 in all. They are offered under Customize → Discover, and each one you install adds its connector.

## Which connectors are listed

A connector is listed when its server lets Claude Desktop register itself for sign-in and returns the vendor's sign-in page. A listing does not guarantee that the vendor completes the sign-in.
