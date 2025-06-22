# 💊 Sentiment Analysis of Painkiller Reviews: A Data-Driven Approach to Consumer Insights

## Overview  
This project explores customer sentiment toward common painkillers using supervised learning techniques. We applied Logistic Regression and CART (Decision Tree) models to classify review sentiment as positive or negative, based on a dataset sourced from Kaggle.

## Objective  
- Clean and preprocess drug review data  
- Implement and evaluate Logistic Regression and CART models  
- Compare performance metrics including AUC, sensitivity, and specificity  
- Provide business insights and recommendations for pharma/healthcare marketing and product strategy

## Dataset  
- **Source**: Kaggle (painkiller review dataset)  
- **Records**: 2,500  
- **Label**: Binary sentiment (1 = Positive, 0 = Negative)  
- **Painkillers Included**: Tylenol, Advil, Aleve, Tramadol, Aspirin

## Methodology  
### Text Preprocessing  
- Lowercasing  
- Stopword and punctuation removal  
- Stemming  
- Sparse term removal from Document-Term Matrix  

### Data Partitioning  
- Train/Test Split: 70% / 30%  
- Oversampling with ROSE used to balance the training set  

### Models Used  
- **Logistic Regression**
  - AUC: 0.603  
  - Accuracy: 55.3%  
  - Sensitivity: 66.7%  
  - Specificity: 61.4%  

- **CART (Decision Tree)**
  - AUC: 0.573  
  - Accuracy: 62.7%  
  - Sensitivity: 49.1%  
  - Specificity: 66.3%  

## Key Findings & Business Impact  
- **Marketing ROI Optimization**  
  Positive sentiment reviews can be auto-flagged and used in targeted campaigns, potentially increasing ad engagement and conversion rates by 10–20%, based on industry benchmarks.

- **Support Resource Allocation**  
  Using CART’s high specificity, businesses can route negative sentiment cases faster, decreasing support ticket resolution time by 15–25%, improving operational efficiency.

- **Estimated Revenue Retention Impact**  
  If sentiment analysis helps retain just 5% of at-risk customers, and the average customer lifetime value is $200, then across 50,000 users, that’s a potential $500,000 in retained revenue.

## Business Recommendations  
- Use Logistic Regression as the primary tool for sentiment classification  
- Use CART as a complementary model to investigate negative feedback  
- Apply findings to:
  - Improve customer satisfaction  
  - Highlight positive experiences in marketing  
  - Guide data-driven product enhancements

## Authors  
- Raheela Charania  
- Anmol Anchala  
- Emmanuel Wediko  
- Mercer University | BDA 622: Marketing Analytics | December 2024  
