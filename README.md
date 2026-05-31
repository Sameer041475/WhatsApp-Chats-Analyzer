## 🌐 Live Demo

[Click Here to Use the App](https://whatsapp-chats-analyzer-hvdl4ylh9p4dmrcmtba5hh.streamlit.app/)

# 📊 WhatsApp Chats Analyzer

A Streamlit-based web application that analyzes exported WhatsApp chat data and provides useful insights, statistics, and visualizations.

## 🚀 Features

- 📈 Total Messages Analysis
- 📝 Total Words Count
- 🔗 Shared Links Count
- 🖼️ Media Messages Count
- 📅 Monthly Timeline
- 📆 Daily Timeline
- 🗓️ Activity Heatmap
- 📊 Most Active Users
- ☁️ Word Cloud Generation
- 🔥 Most Common Words Analysis
- 😀 Emoji Analysis

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Emoji
- URLExtract

## 📂 Project Structure

```
WhatsApp-Chats-Analyzer/
│
├── app.py
├── helper.py
├── preprocessor.py
├── requirements.txt
├── stop_hinglish.txt
└── README.md
```

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/WhatsApp-Chats-Analyzer.git
cd WhatsApp-Chats-Analyzer
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser automatically.

---

## 📤 Export WhatsApp Chat

1. Open WhatsApp.
2. Open the chat you want to analyze.
3. Click on **More Options → Export Chat**.
4. Select **Without Media**.
5. Save the exported `.txt` file.
6. Upload the file to the application.

## 📸 Screenshots

Add screenshots of your application here.

## 📊 Sample Insights

- Number of messages sent
- Most active participant
- Peak chatting hours
- Monthly activity trends
- Frequently used words
- Emoji usage statistics

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

## 🐛 Known Issues

- Works best with exported WhatsApp chats in English.
- Different WhatsApp export formats may require modifications in preprocessing.

## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Sameer Kampa**

GitHub: https://github.com/Sameer041475

---

⭐ If you found this project useful, please give it a star on GitHub!
