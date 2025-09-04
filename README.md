# Customer Sentiment Analysis with Generative AI (AWS Bedrock + Python)

## 📌 Project Overview
This project was completed as the **final capstone** for the *Generative AI for Business with AWS* program (Sept 2024).  
It combines **machine learning** (Python + scikit-learn) with **Generative AI** (AWS Bedrock Claude API) to analyze customer feedback for a logistics company and generate actionable insights.

The case study focuses on **ExpressWay Logistics**, a courier and warehousing provider facing delivery delays, operational inefficiencies, and increasing customer complaints. By applying **sentiment analysis and AI-powered outputs**, the project demonstrates how businesses can monitor satisfaction, automate support, and optimize operations.

---

## 🎯 Business Problem
**Challenges**
- Growing number of negative customer reviews  
- Difficulty in identifying recurring service issues  
- Inefficient manual handling of customer feedback  

**Objectives**
1. Classify customer reviews into **Positive vs. Negative** sentiment.  
2. Evaluate model performance with **Accuracy** and **F1-score**.  
3. Use **Generative AI (AWS Bedrock Claude API)** to generate natural-language predictions and outputs.  
4. Provide recommendations to improve service quality and customer satisfaction.  

---

## 🛠️ Tools & Technologies
- **Programming:** Python (pandas, numpy)  
- **Machine Learning:** scikit-learn (train/test split, evaluation metrics)  
- **Generative AI:** AWS Bedrock Claude API (LLM integration for sentiment prediction and natural-language text generation)  
- **Other Tools:**  
  - **boto3 (AWS SDK):** Authentication and API access  
  - **Hugging Face `datasets`:** Dataset loading and preprocessing  
  - **tqdm:** Progress tracking for loops  
  - **tabulate:** Clean, table-style reporting of metrics  

---

## 📊 Approach
1. **Dataset**  
   - 131 labeled customer reviews (`review`, `sentiment`).  
   - Sentiment categories: **Positive** / **Negative**.  

2. **Data Preparation**  
   - Cleaned and structured reviews with pandas.  
   - Split into training and test datasets.  

3. **Modeling & Evaluation**  
   - Built a sentiment classifier using scikit-learn.  
   - Evaluated performance using Accuracy and F1-score.  

4. **Generative AI Integration**  
   - Used **AWS Bedrock Claude API** to generate natural-language outputs from customer reviews  
   - Prompted Claude to provide **sentiment predictions in plain text**  
   - Demonstrated how this workflow could be extended to **automated review summarization**  

5. **Business Recommendations**  
   - Automate customer support workflows with AI-driven summaries
   - Monitor sentiment trends to guide service improvements  
   - Use insights to reduce delivery delays and improve warehouse operations  

---

## ✅ Key Results
- Delivered an end-to-end **sentiment analysis pipeline** combining scikit-learn classification with Claude-powered natural-language outputs  
- Achieved measurable results with **accuracy and F1-score evaluation**  
- Showed how **Generative AI can complement ML pipelines** by providing human-readable predictions and outputs, with applications in **customer service automation and feedback summarization**  

---

## 📂 Repository Structure
- `ExpressWay_Sentiment_AWS_Bedrock.ipynb` → Final project notebook  
- `courier-service_reviews.csv` → Demo dataset (131 reviews)  
- `README.md` → Project documentation  
