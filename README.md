# Mount-AI-Scholar
# 🏔️ Mount AI: Scholar

> **The complexity translator for students, powered by Llama 3.**
> *Project submitted for the Meta Hackathon.*

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Meta Llama 3](https://img.shields.io/badge/Meta_Llama_3-0466C8?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)

## 💡 Inspiration
Education is often filled with dense and complex texts that discourage students. I wanted to create a tool capable of taking any difficult concept and instantly "translating" it into visual and interactive formats to make learning easier and more accessible.

## 🚀 What it does
**Mount AI: Scholar** allows users to paste text or attach a file, and then uses the intelligence of Llama 3 to generate:
- 📖 **A structured summary** to get straight to the point.
- 🧠 **A visual mind map** (dynamically generated with Mermaid.js).
- 🎯 **A presentation** in clear, easy-to-read bullet points.
- ✍️ **Interactive exercises** (MCQs and open-ended questions) to test your knowledge.

## 🛠️ How we built it
- **Frontend:** React.js with Vite, styled with Tailwind CSS for a modern and smooth interface.
- **Backend:** Node.js / Express.js to secure API calls.
- **Artificial Intelligence:** **Meta Llama 3** model (via the lightning-fast Groq API) with precise Prompt Engineering to force the AI to respond in strict formats (especially for generating valid Mermaid.js code).

## ⚙️ How to run it locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Mount-AI-Scholar.git

