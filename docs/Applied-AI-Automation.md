# Applied AI & Automation Workflows (n8n Portfolio)

This portfolio contains a set of n8n workflows showcasing automation, applied AI, and LLM integration across real-world use cases.

## Included Workflows

1. **Resume Automation Workflow**
   - Stripe Checkout → Payment Metadata → Google Sheets → AI Agents
   - Automates a paid resume editing workflow with structured output and file delivery.

2. **LLM Scraping Workflow**
   - Web crawling + extraction + language models
   - Converts public-facing content into structured data for downstream LLM usage.

3. **Smart Meal Planner & Grocery Workflow**
   - Recipe suggestion + grocery list generation
   - AI-driven nutrition, ingredients, and shopping automation.

4. **LLM Attribution Workflow**
   - Evaluates responses across multiple LLMs
   - Useful for prompt testing, ranking, and model selection.

## Running Locally

To use these workflows in your own n8n instance:

1. Import JSON files:
   - **n8n → Workflows → Import → From File**
2. Add your own API keys as environment variables
3. Execute workflows in n8n

## Notes & Credentials

- All API keys and credentials have been removed.
- Replace missing values via a local `.env` file.
- These workflows are for demonstration/portfolio purposes only.

## Stack / Tools Used

- n8n (orchestration + automation)
- Stripe (payments)
- Google Workspace (Sheets + OAuth)
- Pinecone (vector DB)
- OpenAI + Anthropic + Gemini (LLMs)
- Web scraping / crawling

## Objective

Showcase practical automation with AI systems that connect external services, models, and structured workflows together.
