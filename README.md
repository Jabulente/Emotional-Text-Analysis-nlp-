# **Sentiment Analysis on Emotional Texts**

## **Project Overview**

This project focuses on performing **sentiment analysis** on emotionally rich textual data to classify and understand sentiments based on emotional tones. By processing textual inputs through various natural language processing (NLP) steps and leveraging machine learning techniques, the aim is to uncover underlying emotional sentiment (e.g., positive, negative, neutral) and evaluate frequently used emotional phrases and expressions.

The project not only emphasizes sentiment classification but also explores emotional content through statistical distributions, anagram analysis, and visual storytelling techniques such as word clouds.

---

## **Goals and Objectives**

* To detect and classify the **emotional sentiment** expressed in textual data.
* To **preprocess and clean raw textual data** for optimal performance in sentiment classification.
* To **analyze the distribution of sentiments** across emotional categories.
* To identify **frequently used words and phrases** in each sentiment category using anagram techniques.
* To **visually present insights** through word clouds and statistical plots.
* To provide an end-to-end **NLP-based pipeline** for emotion and sentiment detection.

---

## **Workflow Summary**

1. **Data Inspection**

   * Understanding the structure and content of the dataset.
   * Checking for missing values and data integrity.

2. **Data Cleaning**

   * Handling missing values by imputing with empty strings.
   * Removing duplicate entries to avoid biased sentiment analysis.

3. **Text Preprocessing**

   * Lowercasing all text for uniformity.
   * Removing punctuation, numbers, and stopwords.
   * Tokenizing and lemmatizing text to prepare for analysis.

4. **Sentiment Classification**

   * Using **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to classify texts into sentiment categories (Positive, Negative, Neutral).
   * Attaching sentiment scores and classes to each text input.

5. **Exploratory Data Analysis**

   * Statistical analysis and visual plots to explore sentiment distribution across emotional classes.
   * Bar plots, pie charts, and histograms used to summarize and visualize results.

6. **Anagram & Phrase Frequency Analysis**

   * Performing anagram analysis to extract commonly used phrases and word patterns.
   * Analyzing per sentiment class to reveal distinguishing lexical patterns.

7. **Visualization with Word Clouds**

   * Generating **word clouds** to visualize the most frequent words per sentiment/emotional class.
   * Facilitates quick visual understanding of dominant themes.

---

## **Technology Stack**

* **Programming Language**: Python 3.x
* **Libraries & Tools**:

  * `pandas` – Data manipulation and analysis
  * `numpy` – Numerical operations
  * `nltk` – Natural Language Toolkit for preprocessing
  * `vaderSentiment` – Sentiment classification
  * `matplotlib`, `seaborn` – Visualization
  * `wordcloud` – Word cloud generation
  * `collections` – Frequency analysis
  * `re` – Regular expressions for text cleaning

---

## **Methodologies**

### 1. **Sentiment Detection using VADER**

VADER is a lexicon and rule-based sentiment analysis tool tuned specifically for social media texts. It outputs four metrics:

* Positive
* Negative
* Neutral
* Compound (Overall sentiment score)

Each text input is analyzed, and a corresponding sentiment label is assigned based on the compound score.

### 2. **Text Preprocessing**

To make text suitable for NLP and modeling, the following steps were implemented:

* **Lowercasing** to ensure consistency
* **Punctuation and number removal** to reduce noise
* **Stopword removal** to eliminate irrelevant words
* **Lemmatization** to reduce words to their base forms
* **Tokenization** to break text into individual components

### 3. **Anagram and Frequency Analysis**

Anagram-based techniques were used to find repeated phrases and combinations that frequently appeared in texts under specific sentiment labels. The most common n-grams (bi-grams and tri-grams) were extracted and evaluated.

### 4. **Exploratory Visualizations**

The distribution of sentiments was explored using:

* **Bar plots** to show sentiment frequencies.
* **Pie charts** to highlight sentiment proportions.
* **Word clouds** for intuitive representation of the most common words in each emotional class.

---

## **Results and Insights**

* A clear **dominance of positive sentiments** was observed in certain emotional texts.
* **Negative sentiments** showed more lexical diversity, especially in adjectives and exclamations.
* Frequent phrases like *"feel good"*, *"not happy"*, *"very angry"* were strongly tied to respective sentiment labels.
* Word clouds visually revealed thematic concentrations in each category, reinforcing classification patterns detected by VADER.

---

## **Conclusion**

This project demonstrates how NLP techniques can be applied to analyze emotional content and perform sentiment classification effectively. The integration of both statistical and visual techniques provides a multi-faceted understanding of the data. The final outputs not only include sentiment labels but also valuable linguistic patterns that can be used in real-world applications such as customer feedback analysis, mental health monitoring, or social media content review.

---

## **Future Improvements**

* Integrate deep learning models like **BERT** for enhanced sentiment classification accuracy.
* Deploy the model as an **API or web app** for real-time sentiment detection.
* Include multi-language support for broader application.

---

## **Author**

**Jabulente**
Data Analyst | NLP Enthusiast | Crop & Soil Researcher
[LinkedIn](https://www.linkedin.com/in/jabulente2002) | [GitHub](https://github.com/Jabulente) | [Email](mailto:Jabulente@hotmail.com)
