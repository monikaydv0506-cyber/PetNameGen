🐾 Pets Name Generator

AI-powered pet name creator built with LangChain + Streamlit

Generate fun, unique, and personalized names for any pet — instantly!

✨ Features

🧠 AI-generated pet names based on species, personality & themes

🔗 Built with LangChain (PromptTemplate + Chains
)

🎨 Clean Streamlit UI for smooth interaction

☁️ Deployed on Azure Container Apps with Docker support

🛠️ Tech Stack
Tool	Description	Logo
Python	Core programming language	

LangChain	AI workflow, prompt templates & chains	

Streamlit	Web UI framework for Python	

Docker	Containerization & deployment	

Azure	Cloud deployment platform	
📂 Project Structure
Pets-Name-Generator/
├── .gitignore
├── Dockerfile
├── README.md
├── langchain_helper.py   # LangChain prompt & chain logic
├── main.py               # Streamlit app entrypoint
└── requirements.txt      # Dependencies

🚀 Quick Start
git clone <your-repo-url>
cd Pets-Name-Generator
pip install -r requirements.txt
streamlit run main.py

🐳 Docker (Optional)
docker build -t pets-name-generator .
docker run -p 8501:8501 pets-name-generator

❤️ Credits

Monika Yadav
Student | Faculty Development Trainee

Built with 💙 using LangChain, Streamlit, Docker, and Azure.
