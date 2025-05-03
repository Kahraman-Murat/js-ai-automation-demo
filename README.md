# 🛠️ AI-Powered Damage Report System

> **Note:** This project was inspired by a real job listing.  
> It showcases how to use AI (Google Gemini API) in facility management to automatically classify damage reports from tenants and assign the appropriate tradesperson.

---

## 🚀 Features

- Simple HTML form to submit a damage report
- Uses Google Gemini (Free API) for AI-powered text analysis
- Maps the issue to a relevant trade (e.g., electrician, plumber)
- Returns a fallback message if no relevant trade is found
- Simulates assigning a tradesperson and notifying the tenant

---

## 📦 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/Kahraman-Murat/js-ai-automation-demo.git
cd js-ai-automation-demo
```

2. **Install dependencies:**

```bash
npm install
```

3. **Create a `.env` file:**

In the root directory, create a file named `.env` and add your Gemini API key:

```
GEMINI_API_KEY=YOUR_GEMINI_API_KEY_HERE
```

➡️ You can obtain your API key from [https://makersuite.google.com/app](https://makersuite.google.com/app)

4. **Start the project:**

```bash
node server.js
```

5. **Open in your browser:**

```
http://localhost:3000
```

---

## 🧰 Tech Stack

- Node.js + Express
- Google Gemini API (Free)
- HTML, CSS, JavaScript (Vanilla)

---

## 📄 License

This project is for educational and portfolio purposes. For production or commercial use, additional development and testing are required.
