# 📝 TEST-PAPER-GENERATOR

A simple web-based application to generate test papers dynamically from a pool of questions. Built using **Flask**, this app allows educators to manage, preview, and generate test papers on the fly.

---

## 🚀 Features

- Add and manage questions.
- Generate question papers randomly or by category.
- Clean and simple web UI.
- Organized project structure (Templates, Static, Utils, etc.).

---

## 🗂️ Project Structure

```
TEST-PAPER-GENERATOR/
│
├── Templates/         # HTML templates for rendering UI
├── instance/          # Configurations or database (if needed)
├── static/            # Static files like CSS, JS, images
├── utils/             # Utility functions for question parsing, generation, etc.
│
├── app.py             # Main Flask app
├── questions.txt      # Bank of questions used to generate papers
├── requirements.txt   # Python dependencies
└── README.md          # You are here!
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AusafAnsari/TEST-PAPER-GENERATOR.git
   cd TEST-PAPER-GENERATOR
   ```

2. **Create and activate a virtual environment** *(optional but recommended)*:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**:
   ```bash
   python app.py
   ```

5. **Visit the app**:
   Open your browser and go to: [http://localhost:5000](http://localhost:5000)

---

## 📄 Example `questions.txt` Format

```txt
Q: What is Python?
A: Python is a high-level, interpreted programming language.

Q: What does HTML stand for?
A: HyperText Markup Language.
```

> Make sure questions are well formatted if you're parsing from `questions.txt`.

---

## 📦 Requirements

All dependencies are listed in `requirements.txt`. Major ones include:

- Flask

Install them using:
```bash
pip install -r requirements.txt
```

---

## ✨ Contributing

Feel free to fork the repo and submit PRs! Improvements are always welcome.

---

## 📧 Contact

Made with ❤️ by [Ausaf Ansari](https://github.com/AusafAnsari)
