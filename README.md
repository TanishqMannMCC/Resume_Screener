# 👁️ Resume Screener

Vibriss is an automated Applicant Tracking System (ATS) tool designed to streamline the recruitment process. By leveraging Natural Language Processing (NLP), the application compares multiple resumes against a provided job description and ranks them based on their mathematical similarity.

## 🚀 Key Features
* **Multi-Format Support:** Seamlessly processes both PDF and DOCX resume formats.
* **Intelligent Scoring:** Utilizes Scikit-Learn's **TF-IDF Vectorization** and **Cosine Similarity** to calculate match percentages[cite: 2].
* **Real-time Interface:** Built with **Streamlit** for a smooth, interactive user experience[cite: 2].
* **Exportable Results:** Download screened candidate rankings as a CSV file for HR documentation[cite: 2].

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** Streamlit
* **NLP & Analytics:** Scikit-Learn, NumPy, Pandas[cite: 2]
* **File Parsing:** PyPDF2, docx2txt[cite: 2]



## 📋 How It Works
1. **Text Extraction:** The system parses raw text from uploaded resumes and the job description[cite: 2].
2. **Vectorization:** It converts text into numerical vectors using **TF-IDF**, which highlights important technical keywords while ignoring common stop words[cite: 2].
3. **Similarity Calculation:** **Cosine Similarity** measures the angle between the resume vector and the job description vector to determine the match percentage[cite: 2].
4. **Ranking:** Candidates are sorted from highest to lowest match score for easy evaluation[cite: 2].

## ⚙️ Installation & Usage

pip install -r requirements.txt

streamlit run app.py

---

### **Final Pro-Tip for GitHub:**
Before you push, make sure your folder looks like this:
*   `app.py`
*   `requirements.txt`
*   `README.md`
