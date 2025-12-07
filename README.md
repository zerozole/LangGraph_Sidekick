This project is built using LangGraph and serves as an autonomous sidekick capable of completing user-defined tasks. It integrates the following tools:

Playwright – Web browsing and internet interaction
Wikipedia – Information lookup
Google Serper – Search engine queries
Pushover – Sending notifications
Python REPL – Sandboxed code execution
LangSmith – Observability and progress monitoring

Key Features:

Evaluator Loop that iteratively improves task results until success criteria are met
Manual Success Criteria option for user-defined evaluation
Gradio UI for running tasks, viewing outputs, and interacting with the agent

Project Structure:

tools.py – Defines and configures available tools
graph.py – Sets up the agentic workflow using LangGraph
app.py – Runs the agent, handles resource cleanup, and initializes the Gradio interface

Here is the Graph created for the agent:

<img width="226" height="357" alt="image" src="https://github.com/user-attachments/assets/9993f639-40b9-4eea-bf1a-5ee8d2e786a2" />
