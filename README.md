# Smart Assigner - AI Powered Task Assignment API

This project provides an intelligent task assignment system using FastAPI and Machine Learning. 
It predicts workload balance and salary, and also handles assigning tasks based on skills and complexity.

## 🚀 Features

- Predict employee workload balance and salary.
- Assign tasks based on complexity and skills.
- Built with FastAPI and scikit-learn.

## 📂 Project Structure

```
├── app.py                         # FastAPI main app
├── balanced_simple_hr_ai_dataset.csv  # Dataset used
├── Procfile                      # For Render deployment
├── requirements.txt              # Python dependencies
├── runtime.txt                   # Python version for deployment
```

## ⚙️ How to Run Locally

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Run the API:

```bash
uvicorn app:app --reload
```

3. Access docs at:

```
http://127.0.0.1:8000/docs
```

## 🌐 Live Deployment

You can deploy this project easily using [Render](https://render.com) or similar PaaS platforms.

---

Developed with ❤️ by Ahmed Hesham