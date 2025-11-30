Here’s your **proper, clean, colorful, minimalistic README** version based on your draft. I formatted sections, added spacing, headings, and a placeholder for the Tech Stack logo image so it’s ready for GitHub.

---

# 🐾 Pets Name Generator

> *AI-powered pet name creator built with LangChain + Streamlit*

Generate fun, unique, and personalized names for any pet — instantly!

---

## ✨ Features

* 🧠 **AI-generated pet names** based on species, personality & themes
* 🔗 Built with **LangChain** ([PromptTemplate + Chains](https://python.langchain.com/docs/get_started/introduction.html))
* 🎨 Clean **Streamlit UI** for smooth interaction
* ☁️ Deployed on **Azure Container Apps** with Docker support

---

## 🛠️ Tech Stack

![Tech Stack](/images/tech-stack.png)

| Tool          | Description                            |
| ------------- | -------------------------------------- |
| **Python**    | Core programming language              |
| **LangChain** | AI workflow, prompt templates & chains |
| **Streamlit** | Web UI framework for Python            |
| **Docker**    | Containerization & deployment          |
| **Azure**     | Cloud deployment platform              |

---

## 📂 Project Structure

```bash
Pets-Name-Generator/
├── .gitignore
├── Dockerfile
├── README.md
├── langchain_helper.py   # LangChain prompt & chain logic
├── main.py               # Streamlit app entrypoint
└── requirements.txt      # Dependencies
```

---

## 🚀 Quick Start

```bash
git clone <your-repo-url>
cd Pets-Name-Generator
pip install -r requirements.txt
streamlit run main.py
```

---

## 🐳 Docker (Optional)

```bash
docker build -t pets-name-generator .
docker run -p 8501:8501 pets-name-generator
```

---

## ❤️ Credits

**Monika Yadav**
Student | Faculty Development Trainee

Built with 💙 using LangChain, Streamlit, Docker, and Azure.

---


