### An LLM-powered application which takes user queries related to a database -> converts the query into a SQL query -> executes the query on the db -> returns the result in text and table format✨

### Features: 🪄
1. Uses OpenAI's API to process user queries and convert it into SQL query.
2. The application is able to extract the relevant information from the database based on the query.
3. The list of tables in the database is available on the top in the Streamlit interface. You can use this list to query relevant information.

### Setup: 🧰
1. Clone this repository.
```sh
git clone https://github.com/Aaryan015/Natural-language-to-SQL.git
```
2. Install the necessary libraries
```sh
pip install streamlit openai pandas python-dotenv
```
3. Create a ```.env``` file and place the API key in it.
4. Place a sample database file (.db) in the same directory.
5. Run the application:
```sh
python -m streamlit run app.py
```
6. Input your query.
