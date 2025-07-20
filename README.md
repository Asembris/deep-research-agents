# Deep Research App

A modular research assistant built on the OpenAI Agent SDK.  
Runs multiple specialized agents (planner, search, writer, email) to automate research workflows.

## 📁 Structure

- **local_agents/** – individual agent definitions  
- **deep_research.py** – main entrypoint (run with `uvicorn deep_research:app --reload`)  
- **requirements.txt** – Python dependencies  

## 🚀 Installation

1. **Clone**  
   ```bash
   git clone https://github.com/Asembris/deep-research-agents
   cd deep-research-app
