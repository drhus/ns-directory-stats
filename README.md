# NS Directory Stats

Visual analytics dashboard for the Network School member directory.

## Data

- **2,542 members** scraped from the NS internal directory
- **542 currently on campus**
- **222 long-term** members, **40 core** team

## How to view

Open `index.html` in a browser, or use a local server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Data source

Scraped on 2026-06-05 using [Browser Use Cloud](https://cloud.browser-use.com/) — AI-powered browser automation that navigated the NS directory and extracted member data.

## Charts included

- Member growth over time (monthly joins + cumulative)
- Member type breakdown (regular / long-term / core)
- Gender distribution
- Social platform presence (X, LinkedIn, GitHub, Discord, Farcaster, etc.)
- Role keywords from experience (Founder, Engineer, CEO, etc.)
- Top countries and cities
- Profile completeness (bio, experience, education, socials)
