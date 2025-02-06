# 🤖 **Sentiment Analysis of Public Reactions to Tesla’s Optimus Robot on Reddit**  

📊 **Understanding how Tesla’s ‘We, Robot’ event shaped public sentiment towards the Optimus Robot.**  

## 🚀 **Project Overview**  

Tesla’s Optimus Robot represents a significant leap in AI-driven humanoid robotics. With the unveiling of four groundbreaking technologies, **how did the public react?** This study leverages **Reddit sentiment analysis** to explore shifts in public perception **before and after the ‘We, Robot’ event** on **October 11, 2024**.  

🔍 **Research Question:** *Did the ‘We, Robot’ event change public sentiment towards Tesla’s Optimus Robot?*  

💡 **Key Insights:**  
- Before the event, anticipation and excitement led to **higher positive sentiment scores**.  
- After the event, there was an **increase in neutral discussions**, suggesting **expectations weren’t fully met**.  
- The event **reduced negative sentiment**, indicating a shift towards **cautious optimism**.  

---

## 📂 **Data Collection**  

✅ **Subreddits Scraped:** `r/Tesla`, `r/technology`, `r/robotics`, `r/teslamotors`  
✅ **Time Frame:**  
   - **Section A** (*Before Event*): Sept 30, 2023 – Oct 10, 2024  
   - **Section B** (*After Event*): Oct 11, 2024 – Nov 6, 2024  
✅ **Total Data Points:** **1,762**  
   - 📌 **Posts:** 62  
   - 💬 **Comments:** 1,700  

🚀 **Automated Collection using:** `PRAW (Python Reddit Wrapper API)`

---

## 🛠 **Methodology**  

1️⃣ **Data Preprocessing:**  
   - Removed irrelevant posts/comments.  
   - Tokenization, stop-word removal, and lemmatization for text normalization.  

2️⃣ **Sentiment Analysis with VADER:**  
   - Applied **VADER (Valence Aware Dictionary and sEntiment Reasoner)** to classify sentiment into:  
     - ✅ **Positive (> 0.05)**  
     - 🔸 **Neutral (-0.05 to 0.05)**  
     - ❌ **Negative (< -0.05)**  

3️⃣ **Visualization & Trend Analysis:**  
   - Used **Matplotlib & Seaborn** for clear interpretation.  
   - Compared **pre-event vs. post-event** sentiment scores.  

---

## 📊 **Results & Findings**  

📈 **Average Sentiment Scores:**  
- **Before Event:** **0.186** (higher positivity)  
- **After Event:** **0.156** (neutrality increased)  

📊 **Emotion Distribution:**  
- Pre-event: **Higher negative sentiment** (skepticism about AI & robotics).  
- Post-event: **Increased neutral & positive discussions**, suggesting mixed reactions.  
- The **most upvoted post** had **30,923 upvotes**, indicating **strong community interest**.  

---

## 📌 **Limitations & Future Work**  

⚠ **Limitations:**  
- **VADER** may not fully capture **complex emotions** about AI technologies.  
- **Reddit-only dataset** limits broader sentiment representation.  
- **Two-time-point comparison** restricts tracking **long-term sentiment evolution**.  

🚀 **Future Enhancements:**  
- Expand to **Twitter/X & YouTube** comments for wider sentiment tracking.  
- Implement **deep learning NLP models (BERT, RoBERTa)** for better emotion detection.  
- Track **real-time sentiment changes** over months post-event.  

