# AI-Powered-Consumer-Complaint-Routing-Business-Intelligence-Analytics
Developed an AI-driven consumer complaint triage system using Consumer Financial Protection Bureau (CFPB) complaint data to automate regulatory complaint routing. Leveraged R for data cleaning, feature engineering, and supervised decision tree modeling, and Tableau for exploratory analysis and visualization of 2,000 consumer complaint records.

## Overview

This project develops an AI-powered consumer complaint triage system using Consumer Financial Protection Bureau (CFPB) complaint data. The objective was to automate complaint classification and routing by combining business intelligence, supervised machine learning, and generative AI.

Using over 2,000 consumer complaint records, our team designed a decision-tree framework capable of identifying the appropriate resolution pathway based on complaint characteristics. The resulting business logic was integrated into a GPT4All chatbot that assists with complaint routing, fraud detection, debt verification workflows, and customer support escalation.

---

## Project Objectives

- Analyze CFPB consumer complaint data to identify complaint trends and operational insights.
- Build a supervised decision tree model for automated complaint classification.
- Design an interpretable routing framework for consumer disputes.
- Integrate decision-tree logic into a GPT4All chatbot.
- Improve complaint resolution efficiency while supporting regulatory compliance.

---

## Technologies Used

- **R**
  - Data cleaning
  - Data preprocessing
  - Decision Tree Modeling
  - Feature Engineering
  - Statistical Analysis

- **Tableau**
  - Interactive dashboards
  - Complaint trend visualization
  - Business intelligence reporting

- **GPT4All**
  - AI-powered chatbot integration
  - Automated complaint routing
  - Decision support

---

## Dataset

**Source:**
Consumer Financial Protection Bureau (CFPB)

The dataset contains consumer complaints submitted against financial institutions and credit bureaus, including information such as:

- Product Type
- Issue Category
- Company Response
- Consumer Consent
- Timeliness
- Credit Bureau
- State
- Complaint Narrative

Approximately **2,000 complaint records** were analyzed for this project.

---

## Methodology

### 1. Data Collection

- Imported CFPB complaint dataset
- Selected relevant complaint attributes
- Removed incomplete and duplicate records

### 2. Data Preparation

- Data cleaning
- Missing value handling
- Feature engineering
- Category standardization
- Variable selection

### 3. Exploratory Data Analysis

Using Tableau, complaint trends were analyzed across:

- Complaint types
- Financial products
- Credit bureaus
- Geographic distribution
- Response times
- Resolution outcomes

---

### 4. Decision Tree Development

A supervised decision tree model was created to classify incoming complaints into appropriate resolution workflows.

Primary decision variables included:

- Product Type
- Issue Category
- Credit Bureau
- Fraud Indicators
- Debt Collection Status
- Identity Theft Indicators

The model provides transparent and explainable decision paths for complaint routing.

---

### 5. AI Chatbot Integration

The decision-tree logic was integrated into GPT4All to create an intelligent complaint assistant capable of:

- Classifying complaints
- Recommending next actions
- Guiding consumers through dispute processes
- Escalating high-risk complaints
- Supporting human representatives

---

## Features

- Complaint Classification
- Automated Decision Routing
- Business Intelligence Dashboard
- Explainable Decision Tree
- AI Chatbot Integration
- Fraud Detection Support
- Regulatory Workflow Recommendations

---

## Business Impact

This project demonstrates how artificial intelligence and business analytics can improve customer service operations within financial institutions.

Potential benefits include:

- Reduced manual complaint routing
- Faster response times
- Increased operational efficiency
- Improved consistency in decision making
- Enhanced customer experience
- Better regulatory compliance

---

## Skills Demonstrated

- Business Intelligence
- Data Analytics
- Data Visualization
- Decision Tree Modeling
- Feature Engineering
- Machine Learning
- Process Automation
- Artificial Intelligence
- Generative AI
- Business Analysis
- Regulatory Analytics
- Problem Solving

---

## Key Deliverables

- Data preprocessing in R
- Decision tree classification model
- Tableau dashboards
- Complaint trend analysis
- GPT4All chatbot workflow
- Business recommendations
- Final presentation
- Technical report

---

## Repository Structure

```
├── data/
│   └── CFPB_Complaints.csv
│
├── notebooks/
│   └── Data_Cleaning_and_Analysis.R
│
├── dashboards/
│   └── Tableau_Dashboard.twbx
│
├── decision_tree/
│   └── Complaint_Routing_Tree.pdf
│
├── report/
│   └── Final_Project_Report.pdf
│
├── presentation/
│   └── Final_Presentation.pdf
│
└── README.md
```

---

## Future Improvements

- Deploy the chatbot as a web application.
- Integrate real-time CFPB complaint data through an API.
- Evaluate additional machine learning models such as Random Forest and XGBoost.
- Improve chatbot conversational capabilities using modern large language models.
- Develop a predictive model for complaint severity and resolution time.

---

## Learning Outcomes

This project strengthened my experience in:

- Applying data analytics to real-world business problems
- Building interpretable machine learning models
- Creating business intelligence dashboards
- Translating analytical findings into actionable business recommendations
- Integrating AI technologies into business processes
- Working collaboratively in a team-based analytics project

---

## Authors

**Shraeyas Muthaiah**

---

## Disclaimer

This project was completed for academic purposes using publicly available CFPB consumer complaint data. It is intended to demonstrate analytical, business intelligence, and AI development skills.
