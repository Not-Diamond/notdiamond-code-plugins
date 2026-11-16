# Not Diamond Code plugins

A plugin marketplace for Claude Desktop running on Not Diamond Code. `notdiamond desktop setup` adds it, and Claude Desktop installs its plugin automatically.

## connectors

Lists 40 hosted connectors under Customize → Connectors, for you to sign in to the ones you use:

Apollo.io, Atlassian, Attio, Clay, Clerk, ClickUp, Cloudinary, Common Room, Craft, Egnyte, Fathom, Guru, Hugging Face, Intercom, Jam, Klaviyo, Linear, Lucid, Mailchimp, Mercury, Microsoft 365, Mintlify, Miro, Mixpanel, Monte Carlo, Netlify, Notion, Otter.ai, Outreach, PlanetScale, PostHog, Postman, Pylon, Ramp, Sanity, Sentry, Stripe, Supabase, Todoist, Webflow.

Each connector points at the vendor's own MCP server. Sign-in happens with the vendor, and this repository holds no credentials.

## Which connectors are listed

A connector is listed when its server lets Claude Desktop register itself for sign-in and returns the vendor's sign-in page. A listing does not guarantee that the vendor completes the sign-in.

Claude Desktop offers sign-in only for connectors in a plugin its configuration installs. A connector from a plugin you add yourself under Customize → Discover cannot be connected, so every connector here ships in the one installed plugin.
