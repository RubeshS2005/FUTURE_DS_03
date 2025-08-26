# 📊 Student Feedback Analysis – Task 3  

An internship project by **Future Interns** to analyze **student event/course feedback** using **Data Science & Analytics**.  
The goal is to turn raw survey data into **actionable insights** that can improve campus life and teaching practices.  

---

## 🚀 Project Overview  
This project analyzes feedback (ratings + comments) collected from students after campus events/courses.  
We use **data science and visualization tools** to:  
- Clean and prepare survey responses  
- Analyze rating distributions (1–10 scale)  
- Identify highest- and lowest-rated aspects  
- Generate insights with charts & heatmaps  
- Provide **recommendations for improvement**  

---

## 📂 Dataset  
- **student_feedback.csv** (1001 responses)  
- Columns include:  
  - *Well versed with the subject*  
  - *Explains concepts in an understandable way*  
  - *Use of presentations*  
  - *Degree of difficulty of assignments*  
  - *Solves doubts willingly*  
  - *Structuring of the course*  
  - *Provides support for students going above and beyond*  
  - *Course recommendation based on relevance*  

Cleaned dataset is also saved as:  
- `cleaned_feedback.csv`  
- `cleaned_feedback.xlsx`  

---

## 🛠 Tools & Libraries  
- **Google Colab / Jupyter Notebook**  
- **pandas** – Data cleaning & analysis  
- **matplotlib / seaborn** – Charts & plots  
- **wordcloud** – (optional for text comments)  
- **nltk / VADER / TextBlob** – Sentiment analysis  

---

## 📊 Key Findings  
1. **Overall average rating**: 5.92 / 10  
2. **Top-rated aspects**  
   - Well versed with the subject → 7.50  
   - Explains concepts clearly → 6.08  
   - Use of presentations → 5.94  
3. **Lowest-rated aspects**  
   - Course recommendation relevance → 5.60  
   - Solves doubts willingly → 5.47  
   - Assignment difficulty → 5.43  
4. **Distribution snapshot**  
   - High ratings (8–10): 32.4%  
   - Mid ratings (5–7): 36.2%  
   - Low ratings (1–4): 31.4%  

---

## 💡 Recommendations  
- Improve **low-rated areas** (assignment clarity, doubt-solving, relevance).  
- Reinforce **strengths** (subject knowledge, concept clarity).  
- Focus on **interactive teaching methods** to lift overall satisfaction.  
- Re-measure monthly to track improvements.  

---

## 📌 Deliverables  
- Cleaned datasets:  
  - `cleaned_feedback.csv`  
  - `cleaned_feedback.xlsx`  
- Aggregated results:  
  - `question_averages.csv`  
  - `overall_rating_distribution.csv`  
  - `correlation_matrix.csv`  
- Visualizations:  
  - `hist_per_question.png`  
  - `avg_by_question.png`  
  - `boxplots_by_question.png`  
  - `correlation_heatmap.png`  

---

## 👩‍💻 How to Run  
1. Open in **Google Colab** or Jupyter Notebook.  
2. Install requirements:  
   ```bash
   pip install pandas matplotlib seaborn nltk vaderSentiment wordcloud textblob openpyxl
   ```
3. Upload dataset (`student_feedback.csv`).  
4. Run notebook cells to generate results & charts.  

---

## 🎓 Learning Outcomes  
- Data cleaning & preprocessing  
- Statistical analysis of survey data  
- Visualization with bar plots, boxplots, heatmaps  
- Generating insights & recommendations from real-world data  

---

✨ *This project demonstrates how data science can make student voices count — turning feedback into actions for a better academic experience.*  
