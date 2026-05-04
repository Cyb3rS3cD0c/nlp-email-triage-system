# 📧 AI Email Assistant — NLP Workflow Automation (Graduate Project)

This project implements a complete AI-powered email triage system using a hybrid approach that combines rule-based logic with LLM reasoning. The assistant classifies emails, generates adaptive responses, and evaluates its own output using an LLM-as-a-Judge framework.

This notebook was developed as part of a graduate-level NLP course and demonstrates practical workflow automation, prompt engineering, and model evaluation.

---

## 🚀 Project Overview

Modern inboxes are overloaded. This project builds an intelligent assistant that:

### ✔️ Classifies emails into 6 categories  
- Urgent & High Priority  
- Deadline-Driven  
- Routine Updates  
- Informational  
- Personal/Social  
- Spam/Unimportant  

### ✔️ Generates an Executive Dashboard Summary  
A high-level overview of yesterday’s email activity, including trends, priorities, and recommended actions.

### ✔️ Drafts Email Responses (Adaptive Tone)  
The assistant writes replies using tone appropriate to the category:
- Urgent → concise & action-oriented  
- Deadline → structured & confirming  
- Routine → warm & collaborative  
- Informational → neutral & helpful  
- Personal → friendly & professional  

### ✔️ Evaluates Its Own Responses  
Using an LLM-as-a-Judge rubric, each drafted reply is scored on:
- Clarity  
- Tone  
- Relevance  
- Actionability  
- Professionalism  

---

## 🧠 Technical Highlights

### **Hybrid Classification Model**
- Rule-based keyword matching for speed and transparency  
- LLM fallback for ambiguous cases  
- Ensures accuracy while minimizing token usage  

### **Adaptive Tone Generation**
- Dynamic tone selection based on category  
- Professional, context-aware email drafting  

### **LLM-as-a-Judge Evaluation**
- JSON-based scoring  
- Balanced critique  
- Automated quality assurance  

### **End-to-End Workflow**
- Data ingestion  
- Filtering (Yesterbox method)  
- Classification  
- Response generation  
- Evaluation  
- Final summary  

---

## 📂 Repository Structure

📁 AI-Email-Assistant/
│
├── notebook.ipynb          # Full project notebook
├── README.md               # Project documentation
└── /assets                 # (Optional) Images, screenshots, diagrams


---

## 🛠️ Technologies Used

- Python  
- Pandas  
- OpenAI API (LLM reasoning, drafting, evaluation)  
- Rule-based NLP  
- Jupyter Notebook  

---

## 📊 Key Deliverables

- **Task 1A:** Executive Dashboard Summary  
- **Task 1B:** Urgent Emails  
- **Task 1C:** Deadline Emails  
- **Task 2:** Draft Responses  
- **Task 3:** LLM-as-a-Judge Evaluation  

All tasks are implemented and validated.

---

## 📝 How to Run the Notebook

1. Install dependencies  
2. Add your API key and base URL to `config.json`  
3. Run the notebook top-to-bottom  
4. Export to HTML for submission (instructions included in Section 8)

---

## 🎓 Academic Context

This project was completed as part of a graduate-level NLP course.  
It demonstrates practical AI workflow engineering, hybrid modeling, and evaluation strategies aligned with real-world email automation systems.

---

## 📬 Contact

If you’d like to discuss this project, collaborate, or explore enhancements, feel free to reach out.