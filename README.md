# Social Trends Dashboard

A real-time web dashboard built with React and Recharts that surfaces trending topics from Hacker News, filtered by category with live score data.

**Live demo:** [sinazohari-cs
.github.io/social-trends-dashboard](https://sinazohari-cs.github.io/social-trends-dashboard)

## What it does

- Fetches the top 50 trending stories from the Hacker News API in real time
- Categorizes stories automatically by topic (AI, Web, Science, Security, Startup, Career)
- Visualizes category distribution with an interactive bar chart (Recharts)
- Lets you filter the full story list by category
- Shows live metrics: story count, average score, top source domain, trending category
- Click any story title to open the full article

## Tech stack

- **JavaScript** — no build step, no bundler, runs in any browser
- **React 18** (via CDN) — component-based UI and state management
- **Recharts** (via CDN) — bar chart visualization
- **Hacker News Firebase API** — free, public, no API key required
- **GitHub Pages** — deployment

## How to run locally

Just open `index.html` in your browser. No server needed.

```bash
git clone https://github.com/your-username/social-trends-dashboard
cd social-trends-dashboard
open index.html   # or double-click it
```

## API

This project uses the [Hacker News API](https://github.com/HackerNews/API) — a free, public Firebase REST API:

| Endpoint | Description |
|----------|-------------|
| `/v0/topstories.json` | Returns array of top story IDs |
| `/v0/item/{id}.json` | Returns story details (title, score, url, etc.) |

No API key required. No rate limiting for reasonable usage.

## Project structure

```
social-trends-dashboard/
└── index.html     # entire app in one file (HTML + CSS + JS)
```
