# -Web-Navigator-AI-Agent
Web Navigator AI Agent autonomously interprets user instructions, browses websites, and extracts structured information using local LLMs and browser automation. The agent streamlines complex web tasks such as searching, filtering, and data collection for enhanced developer productivity.

A local AI assistant that executes web browsing tasks based on natural language commands. Users can input queries like “Search Amazon for laptops under 50k and list top 5”, and the agent interprets the command, automates browsing, scrapes relevant data, and presents structured results. Fully offline and privacy-focused.

Features:
Prototype Plan
Backend Setup: Create Node.js + Express server with /api/query endpoint. Configure middleware (body-parser, CORS).
Planner Module: Convert natural language into step-by-step actionable tasks for the automation layer.
Browser Automation: Use Playwright to execute planner steps, navigate websites, extract top results, and structure output.
Frontend: Build React app for instruction input and results display.
Integration & Testing: Connect frontend, backend, planner, and automation modules. Test multiple commands to ensure smooth data flow.
Documentation: Provide setup instructions, folder structure, and usage guide

Key Features:
Natural Language Understanding: Converts user commands into actionable tasks.
Browser Automation: Opens websites, searches, clicks, scrapes data, and handles multi-step workflows.
Structured Output: Presents results in JSON, tables, or CSV files.
Local Execution: Entirely runs on the user’s machine without cloud dependency.

Tech Stack:
LLM: Ollama, GPT4all, LLaMA (for understanding instructions)
Browser Automation: Playwright or Selenium
Backend: Python or Node.js
Optional GUI: Electron.js or Python Tkinter
Data Storage: Local JSON, CSV, or SQLite

Team Contributions 
Member 1 – Backend Core: Set up Node.js server, /api/query endpoint, and middleware.
Member 2 – Planner/AI Logic: Built planner module to convert instructions into actionable steps.
Member 3 – Browser Automation: Implemented Playwright scripts to execute tasks and scrape results.
Member 4 – Frontend (React): Developed UI for command input and result display.
Member 5 – Integration & Testing: Integrated all modules, tested workflow, and documented setup.
