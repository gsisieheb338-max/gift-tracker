# Gift Tracker Mini App — frontend starter

This is a static Telegram Mini App frontend prototype.

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` and `vercel.json`.
2. Import the repository at https://vercel.com/new.
3. Keep the project as a static site (no build command; output directory `.`).
4. After deployment, copy the HTTPS URL into BotFather's Web App URL field.

## Important
- Current account/event rows are demo data only.
- No Telegram user data is collected or stored.
- Telegram WebApp JS is included for in-app sizing/theme integration.
- Before production, add a backend that verifies Telegram `initData` server-side.
- Do not put the bot token in frontend code. Store it only as a server-side secret.
- Real profile discovery, gift upgrades and marketplace listings require a permitted, reliable data source/API; this frontend does not scrape Telegram.
