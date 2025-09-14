# PreceMap 🗺️  
An AI-powered route analysis tool that helps you find the **best travel route** with smart suggestions, detailed breakdowns, and optimization tips.  

---

## 🚀 Features
- Enter **Origin, Destination, and Departure Time**.  
- Get **multiple route options** with estimated travel times.  
- **AI-powered analysis (GPT + Gemini)** to explain:  
  - Which route is optimal and why  
  - Pros/cons of each route  
  - Travel tips (traffic, tolls, road closures, time-of-day considerations)  
- Easy-to-use **web interface** (built with Flask + ngrok for demo hosting).  

---

## 📸 Screenshots
https://drive.google.com/file/d/1244jjBxGuVr7Xdn8oWamLX7UwTslvpUS/view?usp=sharing
*Enter origin, destination, and departure time.*

https://drive.google.com/file/d/18tGC_TNe1M9t2MwIONxg7w6xTTclffCM/view?usp=sharing 
*AI route recommendation with detailed reasoning.*

https://drive.google.com/file/d/16w0BwKQnZvlLn_DMqbqPIuqnJFBUBpk_/view?usp=sharing
*Additional travel tips and cautions.*

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS  
- **Backend**: Flask (Python)  
- **AI Integration**: GPT & Gemini models for route analysis  
- **Deployment**: ngrok (for local-to-public demo)

---

## 📂 Project Structure
```
PreceMap/
│── PreceMap.ipynb        # Colab notebook (core logic + API calls)
│── app.py                # Flask app for route input + results
│── templates/            # HTML templates
│── static/               # CSS / assets
│── screenshots/          # Project screenshots
│── README.md             # Project documentation
```

---

## ▶️ Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/<your-username>/PreceMap.git
cd PreceMap
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run App
```bash
python app.py
```

### 4. Expose with ngrok (optional)
```bash
ngrok http 5000
```

---

## 🌟 Future Improvements
- Live traffic data integration (Google Maps / HERE API)  
- Mobile-friendly UI  
- User profiles & saved routes  
- Voice-based assistant for travel planning  

---

## 🤝 Contributing
Contributions are welcome!  
Feel free to fork, submit PRs, or open issues.

---

## 📜 License
MIT License.  
