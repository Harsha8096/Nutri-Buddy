# NutriBuddy 🥗
A diet plan recommendation system using LLMs and RAG to predict diseases (diabetes, heart disease, thyroid) and generate personalized diet plans.

## Features
- Disease prediction from symptoms.
- Diet plan generation using Llama 3.1 8b LLM.
- Integration with Chroma DB (vector storage) and Postgres (food data).
- Interactive Flask-based chatbot.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/NutriBuddy.git
   cd NutriBuddy
2. Install dependencies:
   ```bash
pip install -r requirements.txt
4. Set up databases:
Configure Chroma DB for vector storage.
Import USDA food data into Postgres.
5. Run the Flask app:
```bash
   python app/routes.py
Access the chatbot at http://localhost:5000.

Input symptoms or select a disease to get a diet plan.
