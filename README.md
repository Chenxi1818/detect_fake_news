# Detect Fake News
Use three vectorization methods (document frequency, TF-IDF within the Bag-of-Words models, and Word2Vec within the Word Embedding models) and four different machine learning models (Gaussian Naive Bayes, Random Forest, Support Vector Machine, and Feedforward Neural Network) to form 12 kinds of classification methods.  

Achieve the best accuracy rate of 93.7%.

## 📊 Dataset
The dataset used in this project is stored on Google Drive due to its size. It contains news articles and metadata designed for text classification tasks (such as fake news detection).

Data Access
- Download Link: [Click here to download the dataset (94MB)](https://drive.google.com/file/d/1ZeXdnR-oSwVRQxXLU5Qv-_EnZgjvAouR/view?usp=drive_link)
- File Format: CSV (Comma-Separated Values)

### Data Dictionary

| Field | Data Type | Description |
| :--- | :--- | :--- |
| **id** | `Integer` | A unique identifier assigned to each individual news article. |
| **title** | `String` | The headline or title of the news article. |
| **author** | `String` | The name of the author(s) who wrote the article (may contain null values). |
| **text** | `String` | The full body text of the news article. |
| **label** | `Integer` | A binary classification label: `1` for unreliable/fake news and `0` for reliable/real news. |
