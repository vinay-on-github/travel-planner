# Travel Planner for Claude Code

An agent that plans your trip from start to finish. It compares flights, recommends hotels with real guest-review highlights, builds a day-by-day itinerary of places to visit and eat, estimates your budget, and wraps it all up in one clear summary with booking links.

> The agent researches and recommends — it does not make bookings or payments. Prices are approximate and change often; always confirm on the booking site.

## Install

In Claude Code:

```
/plugin marketplace add YOUR_GITHUB_USERNAME/travel-planner-marketplace
/plugin install travel-planner@travel-tools
```

## Use

Run the slash command:

```
/plan-trip Goa from Bangalore, 12–16 Jan, 2 adults, ₹60,000 total, beaches and seafood
```

Or just ask naturally — Claude will hand off to the agent:

```
@travel-planner:travel-planner Plan 5 days in Tokyo in April for a family of 4, mid-range budget
```

## What you get

- ✈️ 2–4 flight options (cheapest, fastest, best value) with links
- 🏨 3 hotel picks across your budget, with what reviewers say
- 🗺️ Day-by-day itinerary matched to your interests
- 🍜 Food recommendations
- 💰 Estimated total budget
- 📋 Visa, weather, transport, and a "what to book first" checklist

## What's inside

```
.claude-plugin/marketplace.json          # marketplace catalog
plugins/travel-planner/
  .claude-plugin/plugin.json             # plugin manifest
  agents/travel-planner.md               # the agent
  skills/plan-trip/SKILL.md              # /plan-trip command
```

## License

MIT
