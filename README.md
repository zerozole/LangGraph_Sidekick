This Agentic Ai project is created using langGraph. It is a sidekick which can complete tasks given by the user and has access to the following tools:
1. Playwright for surfing internet
2. Wikipedia to look up for information
3. GoogleSerper for looking up google
4. Pushover for sending notification

This agent has an evaluator which helps it to improves the task completing agent results until the success criteria is met. The success criteria can also be entered manually.
The UI is created using Gradio.

tools.py define the tools that are available.
graph.py sets up the Agentic Workflow using langGraph
app.py helps run the agent, cleanup resources if needed and sets up the gradio UI.

Here is the Graph created for the agent:

<img width="226" height="357" alt="image" src="https://github.com/user-attachments/assets/9993f639-40b9-4eea-bf1a-5ee8d2e786a2" />
