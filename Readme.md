# 🌐 CHROOME-EXTENSION-FOR-TRANSLATION

A Chrome extension that enables instant language translation directly in your browser, powered by Flask and Google Translate.

---

## ✨ Introduction

**CHROOME-EXTENSION-FOR-TRANSLATION** is a browser extension designed to make translating text effortless. With a simple popup UI, users can select their target language and translate any text without leaving their current tab. The extension leverages a Flask backend and the `googletrans` library for accurate translations.

---

## 🚀 Features

- 🌍 **Multi-language Support:** Translate to and from multiple languages using Google Translate.
- ⚡ **Instant Translation:** Get translations instantly from the browser popup.
- 🧩 **Easy Integration:** Simple UI integrated as a Chrome extension.
- 🔒 **CORS Enabled:** Secure communication between extension and Flask backend.

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CHROOME-EXTENSION-FOR-TRANSLATION.git
cd CHROOME-EXTENSION-FOR-TRANSLATION
```

### 2. Set Up the Backend

**Requirements:**
- Python 3.x
- [Flask](https://flask.palletsprojects.com/)
- [Flask-CORS](https://flask-cors.readthedocs.io/)
- [googletrans](https://github.com/ssut/py-googletrans)

```bash
pip install flask flask-cors googletrans==4.0.0-rc1
```

**Run the Flask Server:**
```bash
python app.py
```

### 3. Load the Chrome Extension

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** (top right).
3. Click **Load unpacked** and select the project directory containing `manifest.json`.
4. The extension named "UI" will appear in your browser.

---

## 📖 Usage

1. **Start the Flask backend** as described above.
2. **Click the extension icon** in Chrome.
3. **Enter the text** you wish to translate in the popup.
4. **Select your target language** from the dropdown.
5. **View the translated result** instantly in the popup.

---

## 🤝 Contributing

We welcome contributions! To get started:

1. **Fork** the repository.
2. **Create a new branch** for your feature or fix.
3. **Commit your changes** with clear messages.
4. **Open a Pull Request** detailing your changes.

**Suggestions and bug reports** are also appreciated. Please use [Issues](https://github.com/your-username/CHROOME-EXTENSION-FOR-TRANSLATION/issues) for any feedback.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> **Note:**  
> This extension is for educational and personal use. Please respect the terms of service of Google Translate and related APIs.

---

**Enjoy translating! 🌈**

---

## 📁 Project Structure

```
CHROOME-EXTENSION-FOR-TRANSLATION/
│
├── app.py              # Flask backend for translation
├── index.html          # Extension popup UI
├── index.js            # Popup frontend logic
├── manifest.json       # Chrome extension manifest
└── README.md           # Project documentation
```


## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/Pranesh-2005/CHROOME-EXTENSION-FOR-TRANSLATION
