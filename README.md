# Travel Planner

Plans your trip from start to finish. Tell it where, when, who's going and your budget, and it compares flights, recommends hotels with highlights from recent guest reviews, builds a day-by-day itinerary of places to visit and eat, estimates your total budget, and wraps it all up in one clear summary with booking links.

> The planner researches and recommends — it does not make bookings or payments. Prices are approximate and change often; always confirm on the booking site.

## Install

**Claude.ai or the Claude desktop app (chat and Cowork)**
1. Go to **Customize → Plugins**.
2. Choose **Add → Upload plugin** and select the plugin zip, or **Add → Add marketplace** and enter the GitHub repository that lists this plugin.

A plugin added to your Claude account also appears in Claude Code automatically.

## Use

Ask in plain words:

> Plan a 4-day trip to Goa from Bangalore in January for 2 people, ₹60,000 budget, beaches and seafood

Or use the command:

```
/plan-trip Goa from Bangalore, 12–16 Jan, 2 adults, ₹60,000 total, beaches and seafood
```

In Claude.ai chat, turn on **web search** so the planner can look up flights, hotels and reviews.

## What you get

- ✈️ 2–4 flight options (cheapest, fastest, best value) with links
- 🏨 3 hotel picks across your budget, with what reviewers say
- 🗺️ Day-by-day itinerary matched to your interests
- 🍜 Food recommendations
- 💰 Estimated total budget
- 📋 Visa, weather, transport, and a "what to book first" checklist

## What's inside

```
travel-planner/
├── .claude-plugin/
│   ├── plugin.json            # name, version, author
│   └── icon.png               # listing icon
|   └── marketplace.json       # manifest
├── skills/plan-trip/SKILL.md  # the planner (works in chat, Cowork and Claude Code)
├── agents/travel-planner.md   # same planner as a subagent (Cowork and Claude Code only)
└── README.md
```

## License

MIT
