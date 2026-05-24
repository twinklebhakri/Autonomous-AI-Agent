# 🤖 Autonomous SQL Data Analysis Agent

An agentic AI system that autonomously connects to a 
retail SQL database, independently decides what to 
analyze, writes its own queries, identifies anomalies, 
and generates executive-level narrative insights.

## 🧠 What Makes It Agentic
No predefined questions. The agent:
- Explores the database structure autonomously
- Decides which analysis to run
- Drills deeper when it finds something interesting
- Writes executive commentary on its findings

## 🛠️ Tech Stack
- **LangChain** — agent framework
- **GPT-4o** — reasoning brain
- **SQLAlchemy** — database connection
- **SQLite** — dummy retail database
- **Python/Pandas** — data layer

## 📊 Sample Output
The agent autonomously identified:
- Top performing categories by revenue
- YoY decline anomalies by store
- High volume / low margin paradox in Scarborough
- Brampton as positive outlier with replication recommendation

## 🚀 How To Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Add your OpenAI API key to `.env`
4. Run `setup_db.py` to create dummy database
5. Run `agent.ipynb` and watch it think!

## 💡 Real World Application
Built to simulate automating the manual process of 
retail sales commentary generation — replacing hours 
of analyst work with autonomous AI reasoning.
