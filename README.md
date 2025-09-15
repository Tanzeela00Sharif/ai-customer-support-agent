# ai-customer-support-agent
# 🤖 AI Customer Support Agent (Make.com + Google Workspace)

This project demonstrates an **AI-powered customer support automation system** built with [Make.com](https://www.make.com/) and Google Workspace.  
It automatically processes customer queries, fetches answers from a knowledge base, and sends professional email responses.

---

## 📌 Workflow Overview
1. **Trigger** → A customer submits a query via Google Form.  
2. **Processing** → The AI-agent categorizes the query and retrieves answers from Google Docs.  
3. **Response** → An email reply is sent to the customer via Gmail.  

This reduces manual workload, improves response time, and provides consistent customer support.

---

## 🛠️ Tools & Technologies
- **Make.com** → Workflow automation platform  
- **AI-Agent Module** → Intelligent query understanding  
- **Google Forms** → Collect customer questions  
- **Google Docs** → Store FAQ / knowledge base  
- **Gmail** → Send automated replies  

---

## 📂 Repository Structure
```bash
ai-customer-support-agent/
│
├── README.md                # Project documentation
├── blueprint/
│   └── ai-support.json       # Exported Make.com workflow blueprint
├── images/
│   └── workflow.png          # Visual representation of workflow
└── docs/
    └── workflow-steps.md     # Detailed step-by-step explanation
