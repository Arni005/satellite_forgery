# 🛰️ Satellite Forgery Detection - FastAPI Backend

This is the **backend API** of the Satellite Forgery Detection project. It powers the ML model for detecting tampered satellite images using a Convolutional Neural Network (CNN) trained with **PyTorch**. This backend is built using **FastAPI** for efficient, high-performance APIs.

## 🚀 Features

- 🧠 Deep learning model (CNN with PyTorch)
- 🖼️ Accepts image uploads for forgery analysis
- ⚡ FastAPI-powered backend for high performance
- 📦 JSON responses with detection results
- 📁 CORS-enabled endpoints for frontend integration

---

## 📂 Project Structure
.
├── app/
│ ├── main.py # FastAPI entry point
│ ├── model.py # Model loading & prediction logic
│ └── utils.py # Helper functions
├── requirements.txt # Backend dependencies
├── README.md # You're here!
└── model/
└── my_trained_model.pt # (Local only) PyTorch model file

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Arni005/Satellite_forgery-complete-.git
cd Satellite_forgery-complete-/app

2. Create a virtual environment (recommended)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

▶️ Running the Server
uvicorn main:app --reload

🔗 Frontend Integration
This backend is integrated with an HTML/CSS/JS frontend that sends images via POST /predict to get detection results in real time.

