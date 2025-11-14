AI Post Booster for LinkedIn (n8n Automation Workflow)

Automate your LinkedIn content creation with a single import.

This workflow scrapes viral posts from top creators in your niche, rewrites them using AI, and publishes fresh, high-quality content directly to your LinkedIn profile — fully automated through n8n.

🚀 What This Workflow Does

The AI Post Booster for LinkedIn system is designed to automate the entire content pipeline:

1. Scrapes High-Performing Posts

Pulls top-engaging LinkedIn posts from creators in your niche.

Uses Apify (or your chosen scraper) to collect the content.

2. Rewrites Using AI

Sends each scraped post to your preferred AI model (OpenAI / GPT-4 / GPT-5).

Rewrites the post with:

A unique angle

Your tone of voice

Zero plagiarism

Full readability

3. Auto-Publishes to LinkedIn

Sends the rewritten content directly to your LinkedIn account.

Fully automated posting (daily, scheduled, or trigger-based depending on your setup).

📦 Included in This Repository

AI Post Booster for LinkedIn.json
Ready-to-import n8n workflow file.

🔧 How to Use
1. Download the JSON File

Click the file in this repo and download it to your computer.

2. Import into n8n

Open your n8n dashboard

Go to Workflows → Import from File

Upload AI Post Booster for LinkedIn.json

3. Update Your Credentials

Inside the workflow, you must edit:

Apify API Token (or your scraper credentials)

OpenAI API Key

LinkedIn App / OAuth Credentials

Any additional environment variables you use (optional)

⚠️ The workflow will not run until credentials are correctly set.

4. Adjust Scraper Settings (Optional)

Choose:

Which creators to scrape

How many posts

How often the workflow runs

Your rewrite prompt/tone

5. Activate the Workflow

Once everything is configured:

Click Activate

The automation will start running based on your defined schedule or trigger.
