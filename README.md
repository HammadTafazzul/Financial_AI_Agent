# AI Agents Playground

This project implements an AI-powered playground application using the `phi` framework. The application includes two specialized AI agents:
1. **Web Search Agent**: Performs web searches and provides results with sources.
2. **Finance AI Agent**: Retrieves financial data, including stock prices, analyst recommendations, and company news, using tools like `YFinanceTools`.

## Features
- **Web Search Agent**: Utilizes DuckDuckGo for web searches and returns information in markdown format, always including sources.
- **Finance AI Agent**: Fetches detailed financial data, including:
  - Stock prices
  - Analyst recommendations
  - Stock fundamentals
  - Company news
- **Interactive Playground**: Provides a playground for testing these agents.

## Prerequisites
- Python 3.8 or higher
- API Key for `phi.api` (stored in an environment variable `PHI_API_KEY`)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
