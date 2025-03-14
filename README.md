**GenAI SQL & Python Agent**

A Streamlit-based GenAI assistant for querying SQL databases and generating Python visualizations using Large Language Models (LLMs). This AI-powered tool allows users to interact with databases using natural language and generate Python-based data visualizations seamlessly.


🚀 **Features**

**Natural Language to SQL Query Conversion** – Use GenAI to convert text queries into SQL.

**Python Data Visualization Generation** – Generate Python code for data plots automatically.

**Dynamic Database Connectivity** – Connect to MySQL and execute SQL queries effortlessly.

**Conversational Memory** – Retains context for more meaningful responses.

**Multi-LLM Support** – Select from OpenAI, Llama, or Gemini for enhanced accuracy.

**Streamlit-Based UI** – Intuitive interface for a smooth user experience.


🛠 **Installation**

1️⃣ **Clone the Repository**

git clone https://github.com/yourusername/genai-sql-agent.git
cd genai-sql-agent

2️⃣ **Create a Virtual Environment & Install Dependencies**

python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
pip install -r requirements.txt

3️⃣ **Set Up Environment Variables**

Create a .env file in the project directory and add:

OPENAI_API_KEY=your_openai_api_key
DATABASE_HOST=your_database_host
DATABASE_USER=your_database_user
DATABASE_PASSWORD=your_database_password

4️⃣ **Run the Streamlit App**

streamlit run app.py

