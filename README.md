# Customer Satisfaction & Sentiment Analysis  
### An End-to-End Data Analysis Project using Python & Power BI

This project analyzes **customer satisfaction and sentiment** from 1,462 survey responses related to various ticketing systems. Through a combination of **data preprocessing**, **statistical KPI analysis**, and **text-based sentiment evaluation**, this project provides actionable insights into customer experience and product performance.

---

## 📌 **Project Objectives**
1. Measure customer satisfaction using key KPIs:
   - **CSAT (Customer Satisfaction Score)**
   - **CES (Customer Effort Score)**
   - **NPS (Net Promoter Score)**
2. Perform **sentiment analysis** (Positive, Neutral, Negative) on review text.
3. Visualize insights via an **interactive Power BI dashboard**.
4. Identify key themes from customer feedback using **Word Cloud NLP analysis**.
5. Provide **business recommendations** based on the findings.

---

## 📊 **Key Outcomes**

### **⭐ Data Summary**
- **Total Raw Respondents:** 1,462  
- **Valid Respondents After Preprocessing:** **769**  
- **Validity Rate:** **52.60%**  

### **⭐ KPI Results**
- **CSAT:** 91.86%  
- **CES:** 90.07%  
- **NPS:** 14.04%  

### **⭐ Sentiment Distribution**
- **Positive:** 85.96%  
- **Neutral:** 10.79%  
- **Negative:** 3.25%  

### **⭐ Insights**
- Customers often highlight *ease of use*, *tool performance*, *customer management*, and *features*.
- Negative sentiment tends to focus on *customer service*, *issue handling*, and *timeliness*.
- “Product usability” dominates positive feedback clusters.

---

## 🧠 **Project Workflow**

### **1. Data Understanding**
Dataset includes:
- Numeric ratings (1–5 scale)
- Likelihood-to-recommend (1–10 scale)
- Review text (free text)
- Ticket system used
- Survey date & metadata

---

### **2. Data Preprocessing**
Performed using Python in Google Colab:
- Handling missing values  
- Type casting & normalization  
- Extracting two datasets:  
  - **Rating dataset** → For CSAT, CES, NPS calculations  
  - **Sentiment dataset** → For sentiment scoring & NLP  
- Cleaning review text (lowercase, regex removal, stopwords filtering)
- Tokenization & word frequency generation for Word Cloud  

Complete preprocessing code is available in the **`notebooks/`** folder.

---

### **3. Sentiment Analysis**
- Rule-based sentiment scoring  
- Categorization into **Positive / Neutral / Negative**  
- Word cloud generation using **Python WordCloud**  
- Distribution visualized in Power BI  

---

### **4. Dashboard Visualization (Power BI)**
Interactive dashboard includes:
- KPI Cards (CSAT, CES, NPS)
- Average Rating by Attribute
- Sentiment Classification Donut Chart
- Trend of Sentiment Over Time
- Total Respondents by Ticket System & Sentiment
- Word Cloud  

📌 **Dashboard PDF (Render Preview):**  
https://drive.google.com/file/d/1rURvni0TsKArcEWQa6sLzbjyxyVf7yiH/view?usp=sharing

---

## 📎 **Project Assets**

### 📁 Folder Structure
.
├── data/
│ ├── raw_dataset.csv
│ ├── df_rating.csv
│ └── df_sentiment.csv
│
├── notebooks/
│ └── sentiment_analysis.ipynb
│
├── presentation/
│ ├── Customer_Satisfaction_Presentation.pdf
│ └── Customer_Satisfaction_Presentation.pptx
│
└── Dashboard Sentiment Analysis.pdf


---

## 🎥 **Presentation Video**
Here is my presentation uploaded on LinkedIn 👇  
🔗 https://www.linkedin.com/posts/iftanul-ibnu_today-im-sharing-the-results-of-my-customer-activity-7403242944939667456-mqqI

(*GitHub tidak mendukung upload video langsung, jadi link eksternal sudah sesuai best practice.*)

---

## 🚀 **Technologies Used**
- **Python**
  - pandas
  - numpy
  - matplotlib
  - wordcloud
- **Power BI**
  - DAX (CSAT, CES, NPS formulas)
  - Visualization components  
- **Google Colab** for preprocessing  
- **GitHub** for portfolio documentation

---

## 📝 **Business Recommendations**
1. **Improve Customer Service Quality**  
   The lowest-rated attribute (3.4/5). Prioritize faster response times & agent training.

2. **Enhance Feature Usability**  
   Positive feedback highlights ease-of-use—continue to refine UI/UX elements.

3. **Monitor Negative Sentiments Regularly**  
   Even though low in volume, negative comments reveal operational bottlenecks.

4. **Focus on Proactive Issue Resolution**  
   Many neutral/negative comments mention issue handling & follow-up delays.

5. **Increase Engagement for Promoter Growth**  
   With NPS only at 14%, there is significant potential to convert satisfied users into brand advocates.

---

## 📬 Contact
If you’d like to connect or collaborate:  
**LinkedIn:** https://www.linkedin.com/in/iftanul-ibnu/  
