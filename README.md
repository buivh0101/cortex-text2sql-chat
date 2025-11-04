# Chat with Structured Data (Snowflake + Streamlit)

Interact with data through Snowflake Cortex Analyst. Ask a question. Get SQL. See results. Get an answer.

## Files

- `chat_with_structured_data_app.py` — Streamlit app that calls the Cortex Analyst API and runs SQL in Snowflake.
- `TEXT2SQL_WITH_CORTEX_ANALYST.ipynb` — Notebook for text-to-SQL exploration.

## How it works

1. The app keeps a chat history.
2. It sends messages to Snowflake Cortex Analyst.
3. Cortex returns text, SQL, and suggestions.
4. The app shows the SQL, runs it in Snowflake, then streams an answer from the result set.


