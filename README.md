# IBL Healthcare · MSD Tender Tracker — Option A

## Deploy in 3 steps

1. Push this folder to a GitHub repo
2. Go to vercel.com → New Project → import the repo → Deploy
3. Done. Your dashboard is live at `your-project.vercel.app`

## Connect your Google Sheet

1. Open MSD_TPTS.xlsx in Google Sheets (File → Import)
2. File → Share → Publish to web
3. Select each sheet tab → Comma-separated values (.csv) → Publish
4. Copy the URL for each tab
5. Open your live dashboard and paste the URL

## Auto-refresh
The dashboard auto-fetches new data every 5 minutes from your published sheet.
No login required. Accessible by anyone with the URL.
