# 🚀 AI-Powered Google Sheets Automation (n8n Workflow)

### **Project Overview**
I built an **Intelligent AI Agent** using n8n that interacts with Google Sheets in real-time. This project demonstrates how to build complex AI systems using low-code tools to perform data retrieval and update operations.

### **Key Highlights**
* **AI Agent Reasoning:** Utilized **OpenRouter/Groq** models to analyze user queries and decide when to access the spreadsheet.
* **Memory Integration:** Implemented a `Simple Memory` node to maintain conversational context.
* **Google Sheets as Database:** The workflow uses spreadsheets as a database for fetching and storing records dynamically.

### **Workflow Logic**
1. **Trigger:** Activated when a chat message is received.
2. **Processing:** The AI Agent analyzes the intent of the message.
3. **Action:** If the user asks about a record, the Agent calls the **Google Sheets node**.
4. **Response:** A natural language response is generated based on the sheet's data.

### **Note**
*This project was developed as a Proof of Concept (POC). While the live environment has expired, the architecture and logic are documented through screenshots and the attached PDF.*

