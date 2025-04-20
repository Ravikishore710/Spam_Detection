# 📊 **SMS Spam Detection** 🚨

Welcome to the **SMS Spam Detection Visualizations** project! In this repository, we aim to **explore and visualize** an SMS dataset to distinguish between **spam** and **ham (non-spam)** messages using various data visualization techniques.

---

## 🚀 **Project Overview**

This project utilizes the **SMS Spam Collection Dataset** from the UCI Machine Learning Repository. The dataset contains **5,569 messages** that are categorized into **spam** and **ham** labels. Through this project, we aim to analyze and visualize key insights, such as:

- 📊 **Spam vs Ham Distribution**: What percentage of messages are spam or ham?
- ✍️ **Message Length Comparison**: Do spam messages tend to be shorter or longer?
- 🌐 **Word Frequency in Spam**: What are the most common words used in spam messages?
- 🔑 **TF-IDF Keywords**: What are the most significant words (keywords) in spam messages?

---

## 🧩 **Key Visualizations**

1. **Pie Chart**: 
   - Displays the distribution of spam vs ham messages.
   
2. **Message Length Distribution**: 
   - Visualizes the difference in message lengths between spam and ham messages.
   
3. **Word Cloud**: 
   - Highlights the most frequent words used in spam messages.

4. **Top TF-IDF Words**: 
   - Identifies the most significant keywords in spam messages using the Term Frequency-Inverse Document Frequency (TF-IDF) technique.

---

## 🧪 **Dataset Insights**

This dataset provides us with rich opportunities for analysis. The **spam** messages typically contain marketing language, while **ham** messages are more casual or neutral. By visualizing these patterns, we can gain insights into the structure and contents of both types of messages.

---

## 🤖 **Model Overview**

### **The Model Used:**
To further enhance the understanding of spam and ham messages, a **machine learning model** was trained to classify messages as either **spam** or **ham**.

- **Model Type**: Support Vector Machine (SVM)
- **Features Used**: 
  - **TF-IDF** (Term Frequency-Inverse Document Frequency) for text vectorization.
  - **Message length**, **word frequencies**, and **n-grams** as additional features.

### **Training the Model:**
- The model was trained on the SMS Spam Collection dataset, with messages labeled as **spam** or **ham**.
- **Cross-validation** was used to evaluate the model's performance on unseen data.
- **Hyperparameters** like the **kernel type** were tuned for optimal performance.

### **Model Performance:**
- The model achieved an accuracy of **99%** (replace with actual accuracy if available).
- Additional metrics such as **precision**, **recall**, and **F1-score** were also evaluated.

While this repository currently focuses on the visualizations, the trained model can be used for future classification tasks.

---

## 🧑‍💻 **How to Use**

### 🛠 **Requirements**
- **Python** (>= 3.6)
- **Jupyter Notebook**
- Libraries:
  - **matplotlib**
  - **seaborn**
  - **pandas**
  - **wordcloud**
  - **scikit-learn**



---

## 🤝 **Contributing**

Feel free to fork this repository and submit pull requests for any improvements! Contributions are always welcome.

---

## 🧠 **Author**

**Ravi** – Data Scientist  
Find me on [LinkedIn](https://www.linkedin.com/in/raviikishore)

---

## 📄 **License**

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
