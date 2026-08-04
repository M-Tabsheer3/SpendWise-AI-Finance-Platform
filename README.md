# SpendWise-AI-Finance-Platform
AI-Powered Personal Finance Analytics System using ML (Random Forest, Isolation Forest), 3NF MySQL Database, and LangChain NL-to-SQL Agent with Gradio UI.
#  SpendWise- AI Personal Finance Intelligence Platform

SpendWise is an intelligent, end-to-end financial analytics platform designed to clean, normalize, categorize, and query personal spending data using Machine Learning and Generative AI.

##  Key Features
- **Automated Expense Categorization:** Uses TF-IDF Vectorization & Random Forest Classifier to auto-classify transactions.
- **Anomaly Detection:** Employs Isolation Forest (Unsupervised ML) to flag unusual or potential fraud expenditures.
- **3NF Cloud Database Integration:** Automatically creates and populates a 3rd Normal Form (3NF) relational database hosted on Aiven MySQL.
- **Conversational NL-to-SQL Assistant:** Powered by LangChain and Groq API (Llama 3.3 70B) allowing users to query their database in plain English.
- **Interactive UI:** Built using Gradio with dynamic Matplotlib spending visualization dashboards.

## Tech Stack
- **Language:** Python 3.12
- **Machine Learning:** Scikit-Learn (Random Forest, Isolation Forest)
- **Database:** MySQL (Hosted on Aiven Cloud), SQLAlchemy, PyMySQL
- **Generative AI & Agents:** LangChain, Groq API (`llama-3.3-70b-versatile`)
- **Frontend / UI:** Gradio, Matplotlib, Pandas

##  How to Run on Google Colab
1. Clone this repository or open the `.ipynb` file in Google Colab.
2. Set up your Google Colab **Secrets** with the following keys:
   - `MYSQL_HOST`
   - `MYSQL_PORT`
   - `MYSQL_USER`
   - `MYSQL_PASSWORD`
   - `MYSQL_DB`
   - `GROQ_API_KEY`
3. Upload `Personal_Finance_Dataset.csv` to the Colab runtime.
4. Execute cells 1 through 5 sequentially.
