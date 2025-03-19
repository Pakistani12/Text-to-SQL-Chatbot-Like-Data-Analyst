# Text-to-SQL-Chatbot
This project is a **Text-to-SQL chatbot** built using **Streamlit** and **Groq's LLM** to convert natural language queries into **SQL statements**. The application connects to an SQLite database (`student.db`) and retrieves relevant data based on user input.
## **Features**
- Convert **English queries** into **SQL statements** using Groq's LLM.
- Execute the SQL query on an **SQLite database**.
- Display query results in a **Streamlit web interface**.
- Prevents SQL injection and handles database errors gracefully.

## **Project Structure**
```plaintxt
├── app.py # Main Streamlit application
├── database.py # Script to create the SQLite database
├── requirements.txt # Dependencies
```
1- Create Virtual Environment
```sh
python -m venv venv
venv\Scripts\activate
```
2- Install Dependencies
```sh
pip install -r requirements.txt
```
3- Set Environment Variables

Create a .env file :
```sh
GROQ_API_KEY=""
```
## **Usage**
```sh
streamlit run app.py
```
