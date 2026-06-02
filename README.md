
## 📌 Project Overview
This project is an AI-powered **Travel Planner Agent**. It is built using **IBM Watsonx Orchestrate** and utilizes the **IBM Granite** foundational model to process natural language user requests, build custom itineraries, and evaluate trip budgets.

## 🚀 Live Deployment
The agent is fully deployed and accessible via GitHub Pages! 
👉 **[Click Here to Interact with the Live Agent](https://niva-2008.github.io/Travel-Planner-Agent/)**

## 🛠️ Tech Stack & Architecture
- **AI Core:** IBM Granite Model (via IBM Cloud Lite)
- **Orchestration:** IBM Watsonx Orchestrate
- **Frontend Integration:** Web Chat Channel (Embedded JavaScript Widget)
- **Deployment Platform:** GitHub Pages
- **Knowledge Base Framework:** Retrieval-Augmented Generation (RAG)

## 📂 Repository Structure
- `index.html`: The main web frontend file integrating the live IBM chat widget.
- `global_travel_plans.pdf`: The master RAG knowledge base document containing structured global itineraries and estimated charges.
- `README.md`: Project documentation and submission report.

## 📝 How It Works
1. The user launches the website and opens the chat widget in the bottom-right corner.
2. The user inputs their desired destination, budget constraints, or duration preferences.
3. The **IBM Granite** model extracts context, queries the uploaded `global_travel_plans.pdf` knowledge base, and outputs an optimized, grounded day-by-day itinerary.
