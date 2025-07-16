# 🎭 AI Sentiment Analysis Web App 🚀 

This is an AI-driven **Sentiment Analysis Web Page** with a **modern UI** built using **Tailwind CSS**, and **real-time sentiment visualization** using **Chart.js**. The backend is powered by **Flask and TextBlob** for sentiment detection.

## 🌟 Features:
✅ **Real-time Sentiment Analysis** (Positive, Neutral, Negative)   
✅ **Modern UI with Tailwind CSS**  
✅ **Interactive Chart.js Visualization** for sentiment trends    
✅ **Fast and Lightweight** Flask backend  
✅ **Easy to Deploy & Extend**  

---

## 📌 Tech Stack:
### **Frontend (UI)**
- **HTML, Tailwind CSS** for styling  
- **JavaScript (Fetch API)** to communicate with backend  
- **Chart.js** for real-time sentiment visualization  

### **Backend (API)**
- **Flask** for handling requests  
- **TextBlob (NLTK)** for AI-based sentiment analysis  
- **Flask-CORS** for cross-origin support  

---

## 🚀 Installation & Setup: 
### **1️⃣ Clone the Repository** 
```sh
git clone https://github.com/Akshita27-lab/AI_Sentiment_Analysis-webapp.git
cd sentiment-analysis-webapp
```

### **2️⃣ Install Backend Dependencies** 
```sh
pip install flask flask-cors textblob nltk
```
📌 **One-time setup for TextBlob**  
```sh
python -m textblob.download_corpora
```

### **3️⃣ Run the Backend (Flask Server)** 
```sh
python sentiment_model.py
```
> **Server will run at:** `http://127.0.0.1:5000/`

### **4️⃣ Open the Frontend**
Simply open `index.html` in your browser and start analyzing text! 🎯  

---

## 🖥️ Project Structure:- 
``` 
📁 sentiment-analysis-webapp
 ├── 📄 index.html         # Frontend UI with Tailwind & Chart.js
 ├── 📄 sentiment_model.py # Flask backend with TextBlob sentiment analysis
 ├── 📄 README.md          # Detail Project Documentation
```

---
## 📊 How It Works???
1️⃣ **User enters text** in the input box.  
2️⃣ **Frontend sends a request** to the Flask backend (`/analyze`).  
3️⃣ **Flask processes the text** with **TextBlob AI** and returns a **sentiment score**.  
4️⃣ **Chart.js dynamically updates** the sentiment score on a bar chart.  

---

## 🌟 Example Sentences:
Try analyzing these sample sentences!  

✔️ **Positive:** `"I absolutely love this product! It works perfectly."`  
❌ **Negative:** `"This service is terrible. I'm very disappointed."`  
➖ **Neutral:** `"The meeting lasted for an hour and covered updates."`  
🔄 **Mixed:** `"The design is great, but the performance needs improvement."`  

---

## 🎉 Future Improvements:
🚀 **BERT-based deep learning model** for better accuracy  
🎨 **More UI enhancements** like dark mode & animations  
📊 **Live sentiment tracking** for tweets & news articles  

---
## 🌎 License:
This project is **open-source** under the **MIT License**.   

## 🤝 Contributing-
Contributions are welcome! Feel free to fork the repo and submit a **pull request (PR)**. 

---
## Contact:--

For any questions or feedback, feel free to contact:

Author- Akshita Jangid

Email: jangidakshita68@gmail.com

GitHub: [https://github.com/Akshita27-lab] 

## Screenshots: 
<img width="1918" height="967" alt="Screenshot 2025-03-22 233723" src="https://github.com/user-attachments/assets/91190ce2-60e3-4e37-a566-0ca3a4a7fb6e" />
<img width="1919" height="968" alt="Screenshot 2025-03-22 232552" src="https://github.com/user-attachments/assets/358270e7-dfe5-4056-96bf-a1971cb26ae8" />
<img width="1919" height="974" alt="Screenshot 2025-03-22 232734" src="https://github.com/user-attachments/assets/fa9c47a5-e874-46a1-b794-76b886c066f0" />


## Thank You😊








