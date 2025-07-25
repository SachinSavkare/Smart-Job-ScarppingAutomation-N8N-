# 🚀 Smart Job Scraping Automation Using AI & n8n

Welcome to the GitHub repository of the **Smart Job Scraping Automation** project. This no-code solution helps job seekers automate job discovery, extract ATS-optimized keywords, and get personalized project recommendations — powered by **n8n** and **Google Gemini AI**.

> ⏳ Manual search takes hours. This workflow finds and analyzes jobs for you in minutes.

---

## 📌 Key Features

- 🔍 Automates job search based on your desired role
- 🤖 Uses Google Gemini AI to:
  - Extract ATS-friendly keywords
  - Suggest candidate suitability
  - Recommend matching projects from your portfolio
- 📑 Saves results in a well-structured Google Sheet
- 📷 Easy to understand with a visual workflow (attached below)

---

## 🧠 Why This Project?

Job seekers often:
- Waste time manually scrolling through job platforms
- Miss out on similar titles due to limited keyword use
- Struggle to analyze job descriptions effectively

**This automation solves that.** It makes job searching faster, smarter, and personalized to your own experience.

---

## 🛠️ Tech Stack

| Tool / Service        | Purpose                           |
|-----------------------|------------------------------------|
| `n8n`                 | No-code automation workflow engine |
| `Google Gemini`       | AI agent for JD analysis           |
| `JSearch API (RapidAPI)` | Job listings scraping             |
| `Google Sheets`       | Data storage and output tracking   |

---

## 📌 Project Workflow Overview

1. **Start Manually** via trigger
2. **Enter Job Role** → e.g., `Data Analyst`
3. **Gemini AI generates** alternate job titles
4. **JSearch API fetches** real-time job listings
5. **Each JD is processed** one by one by AI
6. **Gemini extracts:**
   - ATS Keywords
   - Talent Manager Comment
   - Recommended Projects
7. **Results Merged** and stored in Google Sheets

📸 **View Full Workflow Image**:

 ![n8n Workflow](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/WorkFlow.png)

## 📎 Project Documentation

To help you understand, replicate, and present the project clearly, check out the following key documents:

📊 **1. Project Presentation (PPT)** – [Download here](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/PPT.pptx)  
📄 **2. In-Depth Project Report** – [Download here](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/Project%20Report.pdf)  
🛠️ **3. Step-by-Step Project Guide** – [Download here](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/Project%20Guide.pdf)

These files are ideal for interviews, portfolio sharing, and stakeholder walkthroughs.

---

## 🧪 Sample AI Agent Input

```json
{
  "role": "Data Analyst",
  "projects_csv_link": "[Link to your CSV file]"
}
```

📁 **Portfolio Project CSV (Input to AI Agent)**: [Click here](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/DA_Projects.csv)

---

## 📤 Final Output Format

All job data + AI-generated recommendations are saved into Google Sheets:

| Job Title | Company | Apply Link | Keywords | Comment | Recommended Projects |
|-----------|---------|------------|----------|---------|-----------------------|

📈 **View Final Output Sheet**: [Click here](https://github.com/SachinSavkare/Smart-Job-ScarppingAutomation-N8N-/blob/main/DA_Jobs_Saved.csv)

---

## 🧩 How to Use This Project

1. **Import the `.json` file into your n8n workspace**
2. **Set your API keys** for:
   - Google Gemini
   - RapidAPI (JSearch)
3. **Connect your Google Sheet** (pre-auth setup)
4. **Manually trigger** the workflow with your desired role
5. **Let the workflow run and auto-generate insights**

---

## 🎯 Ideal For

- Career switchers looking for project-fit roles
- Freshers with defined portfolios
- Data professionals seeking keyword-rich resumes
- HR tech innovators exploring automation

---

## 📌 Recommended Enhancements

- Schedule the workflow to run daily
- Add email/SMS alerts for job matches
- Add role filters (e.g., Remote only, Salary above X)
- Add a dashboard to view trends and top ATS keywords

---

## 🧠 Author & Credits

Built by **Sachin Savkare**  
As part of an AI + No-Code portfolio to demonstrate practical workflow automation and career enhancement for job seekers.

> 🌟 If you liked this project, consider ⭐ starring the repo and sharing it!

---

**Let automation work while you focus on getting hired.**
