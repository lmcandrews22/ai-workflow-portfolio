# AI Automation & Workflow Systems Portfolio

This repository contains selected n8n workflows showcasing automation and applied AI systems across LLMs, data pipelines, scraping, payments, and task orchestration.

---

##  AI Financial Intelligence Platform (Featured)

AI-powered system that ingests financial transaction data and generates structured, CFO-level insights using LLMs.

### What It Does

* Uploads and stores financial transactions (multi-user support via `user_id`)
* Aggregates and analyzes full datasets
* Uses an LLM to generate structured financial insights
* Stores insights in a database for UI and future querying

### Example Insights Generated

* Largest expense detection
* Profitability summaries
* Revenue vs expense breakdowns
* Spending patterns and anomalies
* Risk and cost optimization opportunities

### Architecture

Frontend UI (built in VS Code)
↓
n8n Workflow (automation + orchestration)
↓
Supabase (Transactions Table)
↓
LLM Analysis (OpenAI)
↓
Supabase (Findings Table for UI consumption)

### Tech Stack

* n8n (workflow automation & orchestration)
* Supabase (Postgres database)
* OpenAI (LLM-powered analysis)
* VS Code (UI + development environment)

### Notes

* Designed as an MVP for real-world financial data ingestion and analysis
* Supports repeated uploads over time (e.g. weekly/monthly financial data)
* Credentials and sensitive endpoints have been removed

---

##  Included Workflows

* **AI Financial Intelligence Platform** (LLM + n8n + Supabase)
* **Resume Automation Workflow** (Stripe + AI + Agents)
* **LLM Scraping Workflow** (Crawling + Extraction + LLM)
* **Smart Meal Planner & Grocery Workflow** (AI recipes + grocery list generation)
* **LLM Attribution Workflow** (Prompt evaluation + model comparison)
* **RAG Chunking Experiments** (n8n + Pinecone + OpenAI)

---

##  Viewing the Workflows

* JSON files are located in the `Workflows/` folder
* Screenshots and supporting assets are located in `docs/`
* Credentials/API keys have been removed for security

---

##  Notes

* All workflows are designed as real-world automation systems, not just demos
* Workflows can be imported directly into n8n via:
  `Import → Workflows → From File`
* Focus is on combining deterministic workflows with AI-driven decision layers

---
