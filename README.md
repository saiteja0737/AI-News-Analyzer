# AI News Analyzer

Keeping up with AI news is overwhelming — new models, funding rounds, research breakthroughs and industry shifts happen every single day. This tool automates that process by scraping top AI news websites, extracting the most important stories, and generating a clean structured digest so you can stay informed in minutes instead of hours.

## What this tool does
- Scrapes multiple AI news sources automatically
- Extracts the top 10 most important AI stories
- Generates a clean structured digest with headlines, summaries and sources
- Runs completely locally using Ollama — no API costs, no data leaving your machine

## How to Use
1. Make sure Ollama is running locally on your machine
2. Pull any Ollama supported model of your choice: `ollama pull mistral` or `ollama pull llama3.2` or any other model from [Ollama's model library](https://ollama.com/library)
3. Update the `model` parameter in the last cell to match your chosen model
4. Add or remove news sources in the `news_sources` list
5. Run all cells
6. Read your AI news digest!

## Requirements
- Ollama installed and running locally
- Any Ollama supported model pulled and ready
- Install dependencies: `uv pip install beautifulsoup4 requests openai`

---
*Built as a Day 2 homework extension for the Udemy course: AI Engineer Core Track — LLM Engineering, RAG, QLoRA, Agents by Ed Donner.*
