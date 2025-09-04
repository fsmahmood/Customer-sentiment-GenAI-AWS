# Customer Sentiment Analysis with Generative AI (AWS Bedrock + Python)
## Project Overview
This project was completed as the **final capstone** for the *Generative AI for Business with AWS* program (Sept 2024).  
It combines **machine learning** (Python + scikit-learn) with **Generative AI** (AWS Bedrock Claude API) to analyze customer feedback for a logistics company and generate actionable insights.

The case study focuses on **ExpressWay Logistics**, a courier and warehousing provider facing delivery delays, operational inefficiencies, and increasing customer complaints. By applying **sentiment analysis and AI-powered summarization**, the project demonstrates how businesses can monitor satisfaction, automate support, and optimize operations.

---

## Business Problem
**Challenges**
- Growing number of negative customer reviews  
- Difficulty in identifying recurring service issues  
- Inefficient manual handling of customer feedback  

**Objectives**
1. Classify customer reviews into **Positive vs. Negative** sentiment.  
2. Evaluate model performance with **Accuracy** and **F1-score**.  
3. Use **Generative AI (AWS Bedrock Claude API)** to summarize feedback and draft customer support responses.  
4. Provide recommendations to improve service quality and customer satisfaction.  

---

## Tools & Technologies
- **Programming:** Python (pandas, numpy)  
- **Machine Learning:** scikit-learn (train/test split, evaluation metrics)  
- **Generative AI:** AWS Bedrock Claude API (LLM integration for summarization & response generation)  
- **Other:** boto3 (AWS SDK), Hugging Face `datasets`, tqdm, tabulate  

---

## Approach
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
   - Leveraged AWS Bedrock Claude API to:  
     - Summarize customer reviews at scale  
     - Generate draft customer service responses  
     - Extract recurring issues from feedback  

5. **Business Recommendations**  
   - Automate customer support workflows with AI-driven summaries.  
   - Monitor sentiment trends to guide service improvements.  
   - Use insights to reduce delivery delays and improve warehouse operations.  

---

## Key Results
- Delivered an end-to-end **sentiment analysis pipeline** for logistics reviews.  
- Achieved classification results with **quantifiable metrics (Accuracy & F1-score)**.  
- Demonstrated **real-world Generative AI use cases** for customer support and operations.  
- Produced recommendations for improving **service quality and customer satisfaction**.  

---
