
# 🧠 AI Legal Advisor & Document Analyzer

A simple, elegant, and lightweight legal support web app that provides:

- 🌐 **Legal Advice Search** for different countries
- 📄 **Legal Document Analyzer** for summarization, key points, and issue identification

Built using:
- 💡 HTML + Tailwind CSS
- 📄 PDF.js and Mammoth.js for document handling
- 🤖 Integrated with LLMs via Groq API for AI-generated content

---

## 🚀 Features

### 🔍 Legal Advice Search
- Select your country
- Enter your legal issue
- Get general AI-based guidance
- Clean UI with gradients and smooth animations

### 📄 Legal Document Analyzer
- Upload `.pdf`, `.txt`, or `.docx` files
- Choose analysis type:
  - Summary
  - Key Points
  - Potential Issues
- Visual progress bar with percentage feedback
- Highlighted AI responses in clean output

---

## 🔧 Setup Instructions

No installation needed. Just open `analyzer.html` in any browser:

```bash
# Step 1: Download repo
git clone https://github.com/yourusername/legal-advisor-analyzer.git

# Step 2: Open the file
cd legal-advisor-analyzer
open analyzer.html  # Or double-click the file
```

> ⚠️ You must have an active internet connection to load TailwindCSS, PDF.js, and Mammoth.js from CDNs.

---

## 🛠️ API Key Setup

This tool is powered by **Groq API** (OpenAI-compatible interface). You need to replace the API key in the HTML:

```javascript
const GROQ_API_KEY = "your_api_key_here";
```

You can get your key from: [https://console.groq.com](https://console.groq.com)


---

## 📌 License

This project is licensed under the **MIT License**.

---

## 🙌 Credits

- [Tailwind CSS](https://tailwindcss.com)
- [PDF.js](https://mozilla.github.io/pdf.js/)
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js)
- [Groq AI](https://groq.com)

---

## 💬 Contact

For questions or feedback email at **imshahzad@gmail.com**
