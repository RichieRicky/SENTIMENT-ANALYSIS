# SENTIMENT-ANALYSIS
This project builds a machine learning model to classify tweets into Positive, Negative, or Neutral sentiments using KNN, RNN, and LSTM models. 
# **Overview**  
Sentiment analysis plays a crucial role in understanding customer perceptions, brand reputation, and product feedback. By leveraging Natural Language Processing (NLP) techniques, businesses can extract meaningful insights from customer reviews, social media comments, and survey responses.  

This project aims to develop a **sentiment classification model** to analyze tweets and categorize them into three sentiment labels:  
- **Positive Emotion** – Indicates favorable sentiment towards the brand or product.  
- **Negative Emotion** – Reflects dissatisfaction or complaints.  
- **No Emotion** – Neutral feedback with no strong sentiment.  

The model is built using **LSTM (Long Short-Term Memory) networks** and **pre-trained GloVe embeddings** to improve text representation. By implementing deep learning techniques, we enhance the accuracy and reliability of sentiment classification.  
# **Business Problem**  
Companies struggle to manually analyze vast amounts of customer feedback on social media. This project aims to automate sentiment analysis of tweets, helping businesses:  

- **Monitor Brand Perception** – Detect positive and negative sentiment trends.  
- **Improve Customer Experience** – Identify complaints and enhance service.  
- **Automate Analysis** – Reduce manual effort and enable real-time insights.  
- **Enhance Marketing & Engagement** – Personalize responses and target key audiences.  

By leveraging deep learning, businesses can make data-driven decisions and optimize customer interactions.  
# **Objectives**  

1. **Automate Sentiment Detection**  
   - Develop an AI-powered model to classify customer sentiments (positive, negative, neutral) with high accuracy.  

2. **Enhance Brand Reputation Management**  
   - Identify and address negative sentiments in real time to improve customer satisfaction and brand perception.  

3. **Optimize Marketing Strategies**  
   - Leverage sentiment insights to refine advertising campaigns, product messaging, and customer engagement.  

4. **Reduce Manual Analysis Effort**  
   - Implement an automated system to analyze large volumes of customer feedback, minimizing reliance on manual labor.  
# **Metrics of Success**  

1. **Accuracy** – Achieve at least 75% accuracy in sentiment multi-class classification.  
2. **F1-Score** – Ensure a balanced F1-score across all sentiment categories to handle class imbalances.  
3. **Confusion Matrix Analysis** – Minimize misclassification rates, especially for negative sentiments.  
4. **Business Impact** – Reduce response time to negative feedback and improve customer satisfaction scores.  
## Data Understanding  

### **1️⃣ Overview of the Dataset**  
The dataset consists of tweets labeled with emotions directed at brands or products for sentiment classification.  
Each row contains:  
- **tweet_text** → The actual tweet text  
- **emotion_in_tweet_is_directed_at** → The brand or product mentioned in the tweet  
- **is_there_an_emotion_directed_at_a_brand_or_product** → The sentiment label (Positive, Negative, or No emotion)  

---

### **2️⃣ Sample Data**  
Below is a preview of the dataset:  

| tweet_text                                            | emotion_in_tweet_is_directed_at | is_there_an_emotion_directed_at_a_brand_or_product |
|------------------------------------------------------|---------------------------------|--------------------------------------------------|
| .@wesley83 I have a 3G iPhone. After 3 hrs twe...  | iPhone                          | Negative emotion                               |
| @jessedee Know about @fludapp ? Awesome iPad/i...  | iPad or iPhone App              | Positive emotion                               |
| @swonderlin Can not wait for #iPad 2 also. The...  | iPad                             | Positive emotion                               |
| @sxsw I hope this year's festival isn't as cra...  | iPad or iPhone App              | Negative emotion                               |
| @sxtxstate great stuff on Fri #SXSW: Marissa M...  | Google                          | Positive emotion                               |

---

### **3️⃣ Data Source**  
[Brands and Product Emotions Dataset](https://data.world/crowdflower/brands-and-product-emotions) 




## CONCLUSIONS

- The automation of sentiment classification reduces manual effort and enables **large-scale tweet analysis**.
- The optimized **KNN model, achieving 75%** accuracy, outperforms the **deep learning model at 62% accuracy**, with well-balanced F1-scores across all classes. Given its superior performance, **KNN is the preferred choice for this classification task**.


## RECOMMENDATIONS

### **1. Adopt the Optimized KNN Model for Sentiment Detection**  
- The KNN model with optimized hyperparameters achieved **75% accuracy** with balanced **precision, recall, and F1-scores** across all sentiment classes.  
- It outperforms the deep learning model (RNN, 62% accuracy), making it the best choice for **reliable sentiment classification** at this stage.  

### **2. Monitor and Address Negative Sentiments in Real Time**  
- Since KNN shows **high recall (92%) for negative emotions**, it can effectively **detect customer dissatisfaction** in real time.  
- Integrating this model into a **real-time monitoring system** will allow proactive issue resolution, improving **brand reputation management**.  

### **3. Use Sentiment Insights to Optimize Marketing Strategies**  
- The model can help analyze **customer sentiment trends**, identifying patterns that inform **advertising strategies and product messaging**.  
- Marketing teams can use insights from sentiment analysis to tailor campaigns that resonate with target audiences.  

### **4. Automate Sentiment Analysis to Reduce Manual Work**  
- The **high accuracy and efficiency of KNN** make it suitable for processing **large volumes of customer feedback**.  
- Automating sentiment classification will reduce **manual effort**, allowing teams to focus on **strategic decision-making rather than manual analysis**.  

### **Next Steps**  
- **Deploy the KNN model** into a sentiment analysis pipeline for real-time monitoring.  
- **Periodically re-evaluate models** and explore advanced deep-learning techniques (e.g., transformers) if further performance improvement is needed.  
- **Incorporate additional data sources** (e.g., social media, customer reviews) to refine sentiment predictions.  

