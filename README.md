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

# Screenshots


<img width="1920" height="819" alt="q0" src="https://github.com/user-attachments/assets/34d71473-f93f-46de-92f8-43f5886adc6c" />

<img width="1920" height="907" alt="q1" src="https://github.com/user-attachments/assets/e3cac523-feb1-4b9d-ac72-39534cf15afe" />

<img width="1920" height="922" alt="p2" src="https://github.com/user-attachments/assets/819cbd45-e25b-4cc9-b2bc-3b3e18d5a971" />

<img width="1920" height="864" alt="p3" src="https://github.com/user-attachments/assets/ad48a404-c8b9-4a4f-874f-d59a51bb82aa" />

<img width="707" height="858" alt="p4" src="https://github.com/user-attachments/assets/658e079d-2527-437d-ab7c-1efb85ab4b61" />

<img width="1920" height="904" alt="p5" src="https://github.com/user-attachments/assets/23af59f1-8902-4bd6-bfa1-57b24c3cf990" />




