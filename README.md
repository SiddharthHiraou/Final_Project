# End-to-End ML Deployment Pipeline

This project showcases an end-to-end machine learning pipeline — from data analysis and model training to deployment via **Streamlit**, **FastAPI**, and **GitHub Pages**.

> 📍 **Live Documentation:** [https://siddharthhiraou.github.io/Final_Project/](https://siddharthhiraou.github.io/Final_Project/)

---

## 📌 Problem Statement

The objective is to analyze customer data to uncover insights and build a machine learning model capable of predicting customer behavior. The model is made accessible through a web interface and REST API.

---

## 🧠 Key Components

### 📊 1. Exploratory Data Analysis (EDA)
- Correlation heatmaps to detect multicollinearity.
- Visualization and cleaning of customer behavior data.
- Feature engineering and transformation.

### 🤖 2. Model Building
- Built classification models (specific model names can be added here).
- Evaluated using metrics like accuracy, precision, recall, and F1-score.

### 🧪 3. Deployment

- ✅ **Streamlit App** for interactive UI.
- ⚙️ **FastAPI Backend** to serve predictions.
- 🌍 **GitHub Pages** for publishing project documentation and notebook outputs.

---

## 🧰 Tech Stack

- Python, Pandas, Scikit-learn, Matplotlib, Seaborn
- FastAPI, Uvicorn
- Streamlit
- GitHub Pages
- Jupyter Notebook

---

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/SiddharthHiraou/Final_Project.git
cd Final_Project
```

### 2. Create Virtual Environment & Install Requirements
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt  # (Add this file if missing)
```

### 3. Run Streamlit App
```bash
streamlit run Streamlit.ipynb
```

### 4. Run FastAPI Server
```bash
uvicorn FastAPI:app --reload
```

---

## 🌐 Deployment Links

- 📘 **Documentation (GitHub Pages)**: [https://siddharthhiraou.github.io/Final_Project/](https://siddharthhiraou.github.io/Final_Project/)

---

## 📁 Project Structure

```
Final_Project/
├── content/                  # Notebook content
├── FastAPI.ipynb            # Backend API logic
├── Streamlit.ipynb          # Streamlit frontend
├── final_project.ipynb      # Core EDA and ML notebook
├── _build/, _config.yml     # Jupyter Book config & build
└── README.md
```

---

## ✍️ Author

**Siddharth Hiraou**  
🔗 GitHub: [@SiddharthHiraou](https://github.com/SiddharthHiraou)

---

## 📄 License

This project is licensed under the **MIT License**.
