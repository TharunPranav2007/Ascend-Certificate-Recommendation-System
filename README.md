# 🚀 Ascend – AI-Powered Certificate Recommendation System

Ascend is an intelligent certificate recommendation system that helps users discover the most relevant courses and certifications based on their interests, skills, and goals.

It leverages Natural Language Processing (NLP) and similarity-based machine learning techniques to provide personalized recommendations through a modern full-stack web application.

---

## 🚀 Live Demo

You can access the deployed application here:

**[https://ascend-app-zeta.vercel.app/](https://ascend-app-zeta.vercel.app/)**

---

## 📌 Features

- 🎯 Personalized certificate recommendations
- 🧠 NLP-based similarity matching (TF-IDF + Cosine Similarity)
- ⚡ Fast API backend using FastAPI/Flask
- 🌐 Modern frontend built with Next.js + TypeScript
- 🎨 Clean UI with Tailwind CSS
- 🔍 Smart query handling and sanitization
- 📊 Scalable architecture for real-world deployment

---

## 🏗️ Tech Stack

### 🧠 Backend
- Python
- FastAPI / Flask
- Scikit-learn
- Pandas
- NumPy

### 🎨 Frontend
- Next.js (React + TypeScript)
- Tailwind CSS
- PostCSS

### ⚙️ Other Tools
- Git & GitHub
- REST APIs
- CSV Dataset Processing

---

## 🧠 How It Works

1. User enters interests or keywords
2. Input is sanitized and processed
3. TF-IDF vectorization is applied
4. Cosine similarity is computed
5. Top matching certificates are returned
6. Results are displayed in an interactive UI

---

## 🏛️ Architecture

```
└── User Input (Frontend - Next.js)
└── API Request
└── Backend (FastAPI/Flask)
└── Text Processing (sanitize.ts)
└── TF-IDF Vectorization
└── Cosine Similarity Calculation
└── Top Recommendations
└── Frontend Display (Tailwind UI)
```


---

## 📁 Project Structure

```
ascend-app/
│
├── app.py
├── courses.pkl
├── embeddings.pkl
├── main.py
├── requirements.txt
├── runtime.txt

└── templates/
    ├── index.html

└── static/
    ├── script.js
    ├── style.css

└── __pyache__
    ├── main.cpython-314.pyc

README.md
```

---

## 🎨 UI & Styling

- Built using Tailwind CSS for rapid styling
- Custom dark theme using CSS variables :contentReference[oaicite:0]{index=0}  
- Responsive and minimal design
- Smooth scroll and UI enhancements

---

## ⚙️ Installation & Setup

### 🔹 1. Clone Repository

```bash
git clone https://github.com/your-username/ascend.git
cd ascend
```

### 🔹 2. Backend Setup
```
cd backend
pip install -r requirements.txt
python app.py
```

Server runs on: http://localhost:5000

### 🔹 3. Frontend Setup
```
cd frontend
npm install
npm run dev
```

Frontend runs on: http://localhost:3000

---

## 🔌 API Endpoint

### Request:
```
{
  "query": "machine learning and AI"
}
```
### Response:
```
[
  "AI Certification by XYZ",
  "Machine Learning Course by ABC"
]
```

---

## 📊 Machine Learning Model
1. TF-IDF Vectorizer
2. Cosine Similarity
3. Text preprocessing & sanitization
4. Content-based filtering approach

---

## 🚀 Future Enhancements
1. 🔐 User authentication system
2. 📊 Recommendation explanation (why this course?)
3. 🤖 Deep learning-based recommendation
4. 🌍 Deployment on cloud (AWS / Vercel)
5. 📱 Mobile app integration

---

## 🤝 Contribution

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a Pull Request

---

## ✍️ Authors

* **Tharun Pranav T** - [LinkedIn Profile](https://www.linkedin.com/in/tharun-pranav-t-274a18327?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
