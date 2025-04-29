
# AgileGPT Workspace: AgileBot MVP 🚀

A lightweight Agile project management assistant powered by GPT-4o.

This is the first version (MVP) of AgileBot, focused on:
- Setting an Objective
- Generating an Agile Plan (user stories / tasks)
- Managing Sprints and task progress
- Preparing for future upgrades (memory management, file context, task evolution)

---

## 📦 Project Structure

```plaintext
agilegpt_workspace/
├── bots/
│    └── agilebot/
│         ├── objective_manager.py
│         ├── plan_manager.py
│         ├── sprint_manager.py
│         ├── memory_manager.py
│         └── gpt_agent.py
│
├── ui/
│    └── main_dashboard.py
│
├── data/
│    ├── sessions/
│    └── uploads/
│
├── app.py
├── requirements.txt
├── README.md
├── .env
```

---

## 🚀 How to Run

1. Clone the repo and navigate to the project root.

```bash
git clone https://github.com/kstar1/agilegpt_workspace.git
cd agilegpt_workspace
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file and add your OpenAI API key:

```plaintext
OPENAI_API_KEY=your_openai_api_key_here
```

4. Launch the app:

```bash
streamlit run app.py
```

---

## 🎯 Features in AgileBot MVP

- [x] Set and update a working Objective
- [x] Generate Agile Plan via GPT-4o
- [x] View Agile Plan as tasks/stories
- [x] Basic Sprint manager (track progress)
- [x] Upload files (future expansion slot)

---

## 🛠️ Planned Future Enhancements

- Memory summarization when token usage grows
- Task evolution and sprint replanning based on GPT insights
- File-based context expansion (dynamic knowledge loading)
- Additional specialized bots (e.g., RAGBot, CodeBot)

---

## ⚡ Requirements

- Python 3.8+
- Streamlit
- OpenAI Python SDK
- python-dotenv

---

## 📣 Notes

This is an MVP built for modular expansion:
- Easy to add new Bots
- Extendable UI
- GPT planning separated cleanly from UI/logic
- Optimized for consulting-grade tool development

---

## 🔗 License

This project is currently personal-use only. No formal license applied.

---
