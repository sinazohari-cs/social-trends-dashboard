# Social Trends Dashboard

A web dashboard that tracks what's trending on Hacker News and visualizes the data in real time.

I built this project to get more experience working with APIs, React state management, and data visualization. The dashboard fetches live stories from Hacker News, groups them into categories, and displays useful insights about current trends.

**Live Demo:** https://sinazohari-cs.github.io/social-trends-dashboard

## Features

* Fetches the top 50 stories from Hacker News
* Automatically groups stories into categories such as AI, Web Development, Science, Security, Startups, and Career
* Displays category distribution using an interactive bar chart
* Allows users to filter stories by category
* Shows live statistics, including:

  * Number of stories
  * Average story score
  * Most common source domain
  * Current top category
* Links directly to the original articles

## Technologies Used

* JavaScript
* React 18
* Recharts
* Hacker News API
* GitHub Pages

## Running Locally

No installation or build tools are required.

```bash
git clone https://github.com/your-username/social-trends-dashboard
cd social-trends-dashboard
open index.html
```

You can also simply download the project and open `index.html` in your browser.

## About the Data

The dashboard uses the public Hacker News API to retrieve story information in real time.

Endpoints used:

* `/v0/topstories.json` – returns the IDs of top stories
* `/v0/item/{id}.json` – returns details for an individual story

No API key is required.

## Project Structure

```text
social-trends-dashboard/
└── index.html
```

The entire application is contained in a single HTML file, including the React components, styling, and JavaScript logic.

## What I Learned

This project helped me gain hands-on experience with working with external APIs, processing and organizing data, building interactive React interfaces, and creating visualizations that make data easier to understand.
