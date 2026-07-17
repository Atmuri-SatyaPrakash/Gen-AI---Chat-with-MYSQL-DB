# 🦜 Chat with SQL Database using LangChain & Groq

A Generative AI application that enables users to interact with SQL databases using natural language. Built with **LangChain**, **Groq LLM**, **Streamlit**, and **SQLAlchemy**, this application converts user questions into SQL queries and retrieves the relevant information from the database.

---

## 🚀 Features

- 💬 Chat with SQL databases using natural language
- 🗄️ Supports both **SQLite** and **MySQL**
- 🤖 Powered by **Groq Llama 3.3 70B Versatile**
- 🔗 Uses LangChain SQL Agent for SQL query generation
- ⚡ Interactive Streamlit user interface
- 📝 Displays the reasoning steps while generating SQL queries

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- SQLAlchemy
- SQLite
- MySQL
- MySQL Connector Python

---

## 📂 Project Structure

```
Chat-with-SQL-Database/
│
├── app.py
├── student.db
├── requirements.txt
├── README.md
└── screenshots/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YourUsername/YourRepository.git
```

### 2. Navigate to the project

```bash
cd YourRepository
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
streamlit run app.py
```

---

## 🔑 Groq API Key

Generate your free API key from:

https://console.groq.com/keys

Enter the API key in the Streamlit sidebar before interacting with the chatbot.

---

## 💾 Supported Databases

### SQLite

The repository includes a sample SQLite database (`student.db`) for quick testing.

### MySQL

To connect your own MySQL database, provide:

- Host
- Username
- Password
- Database Name

in the Streamlit sidebar.

---

## 💡 Example Questions

- Show all students.
- Display all records from the STUDENT table.
- How many students are there?
- Who scored the highest marks?
- Show students from Section B.
- What is the average marks?
- Sort students by marks.

---

## 📸 Screenshots

### Home Page

![Home Page](screenshots/home.png)

### SQLite Demo

![SQLite Demo](screenshots/sqlite-demo.png)


### MySQL Demo

![MySQL Demo](screenshots/mysql-demo.png)

---

## 🎥 Demo



---

## 📚 What I Learned

- Building SQL Agents using LangChain
- Connecting SQLite and MySQL databases
- Using SQLAlchemy for database connectivity
- Prompt-based SQL query generation
- Integrating Groq LLM with LangChain
- Building interactive AI applications using Streamlit

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is intended for learning and educational purposes.

---

## 👨‍💻 Author

**Atmuri Satya Prakash**

- GitHub: https://github.com/YourUsername
- LinkedIn: https://linkedin.com/in/YourProfile
