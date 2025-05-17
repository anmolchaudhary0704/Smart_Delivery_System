# SwiftPath: A Smart Delivery Optimization System

A simulation platform for autonomous drone-based delivery logistics over real Dehradun city data. Built using **Flask**, **JavaScript**, and **CSV-based location graphs**, it models smart delivery systems of the future.

## 🚀 Features

- 🛰️ Real-time drone delivery simulation
- 📍 Shortest path calculation using **Dijkstra’s Algorithm**
- 🤖 Smart drone selection using **greedy logic**
- 🧠 Flight height determination with **sorting**
- 🔐 Role-based login (Admin & User)
- 📊 Admin dashboard (in-progress)
- 🗺️ Real-world location dataset of Dehradun

## 🛠️ Tech Stack

- Python + Flask (Backend)
- HTML/CSS + JavaScript (Frontend)
- SQLite (Database)
- CSV files for graph modeling of the city

## 📁 Project Structure

```
SMART_DELIVERY_SYSTEM/
├── app.py                    # Main Flask backend logic
├── templates/index.html      # Frontend UI
├── static/script.js          # Delivery simulation logic
├── dehradun_locations.csv    # Graph of real city nodes
├── static/                   # Static assets (JS/CSS)
├── templates/                # HTML templates
```

## ⚙️ How to Run Locally

### 📦 Step 1: Extract the ZIP
Unzip the project folder if you downloaded a ZIP file.

### 💻 Step 2: Open Terminal & Navigate

```bash
cd path/to/SMART_DELIVERY_SYSTEM-main
```

### 🐍 Step 3: (Optional) Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# or
source venv/bin/activate     # macOS/Linux
```

### 🔧 Step 4: Install Dependencies

```bash
pip install flask
```

(Or use `pip install -r requirements.txt` if present)

### 🚀 Step 5: Run the App

```bash
python app.py
```

Open your browser and visit: `http://127.0.0.1:5000`

## ☁️ Pushing to GitHub

### 1. Initialize Git

```bash
git init
git add .
git commit -m "Initial commit - SwiftPath delivery system"
```

### 2. Create a Repo on GitHub (e.g. `smart_delivery_system`)
Copy the HTTPS repo link.

### 3. Push Your Project

```bash
git remote add origin https://github.com/anmolchaudhary0704/Smart_Delivery_System.git
git branch -M main
git push -u origin main
```

## 📚 License

This project is open-source and free for educational use.
