# 🗣️ Martin Luther King Jr. "I Have a Dream" Speech – Text Mining Analysis

## 📌 Project Overview

This project performs a **text mining analysis** on one of the most iconic speeches in American history — Dr. Martin Luther King Jr.’s *“I Have a Dream”*. Delivered during the 1963 March on Washington, the speech advocates for freedom, justice, and equality.

Using **R programming**, the project extracts meaningful insights by analyzing frequently used words, exploring their associations, and visualizing the results using word clouds and bar plots.

---

## 📚 Objective

To understand the **themes**, **emphasis**, and **rhetoric** in King’s speech by:
- Cleaning and preprocessing the text
- Identifying the most frequent and meaningful terms
- Visualizing term frequencies and associations
- Reflecting on the sociopolitical context conveyed through word usage

---

## 🛠️ Tools & Packages Used

- **R programming**
- `tm` – Text Mining
- `SnowballC` – Word stemming
- `wordcloud` – Word cloud generation
- `RColorBrewer` – Color palettes for visualizations

---

## 🔍 Text Mining Workflow

### 1. **Data Collection**
- Speech text was loaded from a public URL.

### 2. **Text Preprocessing**
- Converted all text to lowercase
- Removed:
  - Numbers
  - Punctuation
  - Common English stopwords (e.g., "the", "and", "is")
  - Custom stopwords
- Applied **text stemming** to reduce words to their root forms
- Constructed a **Term Document Matrix (TDM)**

### 3. **Frequency Analysis**
- Terms were sorted based on frequency
- Top words were extracted for further analysis

### 4. **Visualization**
- **Word Cloud**: Highlights the most frequent words in the speech
- **Bar Plot**: Displays the top 10 most common terms quantitatively

### 5. **Term Associations**
- Explored word associations, especially around key terms like `"freedom"`

---

## 📊 Key Insights

- Most frequent terms include: **"will", "freedom", "ring", "dream", and "day"**
- The repetition of *“freedom”* emphasizes the core message of the civil rights movement
- *“Dream”* reflects King’s vision of racial harmony and hope
- *“Ring”* frequently appears in the context of *“let freedom ring”*, symbolizing national unity

---

## 📈 Visuals

- **Word Cloud**: Quickly conveys central themes like *freedom*, *dream*, and *will*
- **Bar Plot**: Confirms that *will* and *freedom* are the most frequently used terms

---

## 🧠 Reflections

This analysis shows how King's deliberate choice of words reinforces his **vision of justice and equality**. Text mining enables a deeper understanding of the rhetoric and enduring power of his speech.

---

## 📂 Repository Contents

- `MLK_R_Codefile` — R code and other necessary files for text mining and visualization
- `MLK_Report.pdf` — Project Report
- `LinktoMLKSpeech.txt` — Text file with link to *I have a Dream* Speech
- `README.md` — Project Documentation

---

