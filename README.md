# Customer Sentiment Analysis with Generative AI (AWS Bedrock + Python)

## 📌 Project Overview
This project was completed as the **final capstone** for the *Generative AI for Business with AWS* course (Sept 2024). It combines **machine learning** (Python + scikit-learn) with **Generative AI** (AWS Bedrock Claude API) to analyze customer feedback for a logistics company and generate actionable insights.

The case study focuses on **ExpressWay Logistics**, a courier and warehousing provider facing delivery delays, operational inefficiencies, and increasing customer complaints. By applying **sentiment analysis and AI-powered outputs**, the project demonstrates how businesses can monitor satisfaction, automate support, and optimize operations.

---

## 🎯 Business Problem

**Challenges**
- Growing number of negative customer reviews  
- Difficulty in identifying recurring service issues  
- Inefficient manual handling of customer feedback  

**Objectives**
1. Classify customer reviews into **Positive vs Negative** sentiment  
2. Evaluate model performance using **Accuracy** and **F1-score**  
3. Use **Generative AI (AWS Bedrock Claude API)** to generate natural-language predictions and outputs.  
4. Recommend business actions to improve customer satisfaction and service quality  

---

## 🛠️ Tools & Technologies
- **Programming:** Python (pandas, numpy)
- **Machine Learning:** scikit-learn (train/test splitting, evaluation metrics)
- **Generative AI:** AWS Bedrock Claude API (LLM integration for sentiment prediction and natural-language text generation)
- **Supporting Libraries:**
  - `boto3` — AWS SDK
  - `tqdm` — tracks progress for evaluation of zero-shot and few-shot prompts
  - `tabulate` — clean, table-style reporting of metrics

---

## 📊 Approach

### 1️⃣ Dataset
- 131 labeled customer reviews (`review`, `sentiment`)
- Sentiment categories: **Positive** / **Negative**

### 2️⃣ Data Preparation
- Data cleansing and structuring with pandas
- Train/test split for supervised learning

### 3️⃣ ML Modeling & Evaluation
- Built a sentiment-classification model using scikit-learn
- Evaluated with **Accuracy** and **F1-score**

### 4️⃣ Generative AI Integration (AWS Bedrock Claude)
Claude was prompted to classify reviews as **Positive** or **Negative** and generate natural-language responses.  
Two prompting methods were tested:

| Prompt Type | Description |
|-------------|-------------|
| Zero-Shot Prompt | Claude predicts sentiment without prior examples |
| Few-Shot Prompt | Claude is provided examples of Positive and Negative reviews before prediction |

---

## 🔬 Experimental Findings (Conclusion)

Based on evaluation against the ground-truth sentiment labels in `courier-service_reviews.csv`:

| Model Variant | Accuracy |
|--------------|----------|
| Zero-Shot Prompt | **86%** | 
| Few-Shot Prompt | ⭐ **98%** | 

➡ **The Few-Shot Prompt clearly outperformed the Zero-Shot Prompt**, outperforming it by 12 percentage points and producing significantly more reliable sentiment judgments.

---

## 🧠 Recommendation

We recommend adopting the **Few-Shot Prompt model** for future customer-feedback monitoring because it is:

- Highly accurate  
- More robust across unseen review text  
- Well-suited for automating large-scale sentiment analysis

Automating sentiment scoring using the Few-Shot Prompt can:

- Reduce manual review workload  
- Accelerate customer-support response times  
- Reveal recurring operational issues earlier  
- Ultimately increase customer satisfaction at ExpressWay Logistics

---

## 🚀 Key Results

- Delivered a complete **ML + GenAI sentiment-analysis pipeline** combining scikit-learn classification with Claude-powered natural-language outputs
- Demonstrated the business value of **prompt-engineering optimization**
- Showed how Generative AI can convert model predictions into **human-readable insights** for customer-service teams

---

## 📂 Repository Structure
| File | Description |
|------|-------------|
| `ExpressWay_Sentiment_AWS_Bedrock.ipynb` | Final project notebook |
| `courier-service_reviews.csv` | Dataset of 131 labeled customer reviews |
| `README.md` | Project documentation |

---

