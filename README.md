# 🚀 AI Post Booster for LinkedIn (n8n Automation Workflow)

Automate your entire LinkedIn posting pipeline with a single ready-made n8n workflow.

This system:
- Scrapes high-performing LinkedIn posts from creators in your niche  
- Rewrites them using AI in your own tone  
- Publishes them directly to your LinkedIn profile  

All 100% automated.

---

# 🔥 Features

## 1. Scrape High-Performing LinkedIn Posts
- Scrapes top posts from creators in your niche  
- Uses Apify or any compatible dataset  
- Fully configurable

## 2. AI Rewrite Engine
- Rewrites scraped posts using GPT  
- Unique, human-like, non-plagiarized content  
- Customizable prompt, tone, style

## 3. Auto-Publish to LinkedIn
- Publishes directly to your LinkedIn profile  
- Optionally create drafts, store in Sheets/Notion, or schedule posts  
- Zero manual work

---

# 📦 Included in This Repository

```
AI Post Booster for LinkedIn.json
```

This is a **ready-to-import n8n workflow**.

---

# 🛠️ How to Use

## Step 1 — Download the JSON File
Download the file from this GitHub repo:  
`AI Post Booster for LinkedIn.json`

## Step 2 — Import into n8n
1. Open your n8n instance  
2. Go to: **Workflows → Import → From File**  
3. Select the JSON file  
4. The full workflow will load instantly

## Step 3 — Update Your Credentials
Open each credential node inside the workflow and update:

- **Apify API Token**  
- **OpenAI API Key**  
- **LinkedIn OAuth / App Credentials**  

> ⚠️ Without valid credentials, the workflow will NOT run.

---

# ⚙️ Customize the Workflow (Optional)

## Scraper Settings
- Change creator usernames  
- Modify number of posts scraped  
- Adjust scraping frequency (daily, weekly, custom)

## AI Rewrite Settings
Inside the AI node, edit:
- Tone  
- Style  
- Creativity  
- CTA  

## Publishing Settings
Modify the final LinkedIn node:
- Publish immediately  
- Create draft  
- Log only  
- Save elsewhere (Sheets, Notion, Airtable)

---

# 🧩 Workflow Diagram

```
[Schedule Trigger]
        ↓
[Scrape Posts (Apify)]
        ↓
[Clean & Prepare Data]
        ↓
[AI Rewrite (OpenAI)]
        ↓
[Formatter → Final Text]
        ↓
[Publish to LinkedIn]
        ↓
[Log Output]
```

---

# 🧪 Testing

1. Run the workflow manually  
2. Inspect the rewritten content  
3. Use “Create Draft” before posting live  
4. Activate workflow when ready  

---

# 📝 Notes

- Works on cloud or self-hosted n8n  
- Fully modular — extend or modify any part  
- Can be connected to multi-platform posting  
- Supports analytics and logging

---

# 🤝 Contribute

Pull requests, suggestions, and improvements are welcome.

---

# ⭐ Support

If this project helped you, please ⭐ star the repository.  
Your support encourages more open-source automations.

