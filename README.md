## Multi-Agent-Financial-Trading-System

A comprehensive agent-based platform for automated financial data analysis, trading strategy evaluation, market sentiment analysis, and risk management.

### Overview

This project uses the CrewAI's multi-agent framework to organize the workflow of financial market analysis, trading strategy development, risk management, and reporting. Multiple intelligent agents operate in a hierarchical format to handle live data collection, news and trend extraction, price analysis, and trading decision making.

### Features

- **Multi-agent Architecture:** Six AI agents handle specific financial analysis tasks, working together in a harmonic workflow.
-**Intelligent Automation:** Searching, gathering and processing market and sentiment data from multible sources with minimal amnual intervention.
-**Social Sentiment Analysis:** Extracting and analysing sentiment automatically from the Stocktwits social platform.
  
-**Comprehensive Risk Evaluation:**  A detailed analysis for risk with recommendations for mitigation.
-**Extansible and Scalable:** An adaptable framework allows for easy addition of new agents, asset types, or reporting modules.
-**All-inclusive Reporting:** Generating a professional automated Markdown/HTML reports with excutive summaries and practical insights.

 ### Requirements

- **Python 3.11** - Core programming language.
- **Jupyter Notebook/JupyterLab** - The environment of development and execution.
- **Dotenv** - For environment variables.
- **CrewAI** - Multi-agent framework for AI coordination.
-**LangChain OpenAI**- AI model integration and management.
- **AI Agents** - Specialized autonomous asgents for different tasks.
- **Web APIs** - SerperDev for web search, ScrapeGraph AI for web scraping.
- **TextBlob** - Natural language processing for sentiment analysis.
-**Requests**- API interactions with financial data sources.

### Agent Architecture

**1. Data Analyst Agent** Monitors and analyzes real-time and historical price market.
**2. Market Sentiment Analyst Agent** scrapes and analyse sentiment from Stocktwits discussions and social media, and applies Natural Language Process (NLP) sentiment scoring.
**3. Trading Strategy Developer Agent** Develops and evaluates trading strategies.
**4. Execution Agent** Suggest optimal trade execution strategies and timing based on strategy output.
**5. Risk Management Agent** Evaluate the risks associated with trading strategies and and provide insights.
**6. Report Agent** Compiles analysis by synthesizing insights into readable reports.

### Installation and Setup

1. Download the repository.
2. Install the required Python packages.
3. Create a `.env` file in the root directory to store your API keys:
```python
   OPENAI_API_KEY=your_openai_api_key
   SERPER_API_KEY=your_serper_api_key
   OPENAI_MODEL_NAME=gpt-4.1-mini
```
4. Open the Jupyter Notebook and configure your analysis parameters.
5. Run the cells.

### Output Files

The project generates complete financial analysis report. 
 `{stock_symbol}_Analysis.md` 

###  Acknowledgments

- Built with [CrewAI](https://www.crewai.com). 
- Uses [OpenAI](https://openai.com) models.  
- Search powered by [Serper](https://serper.dev).
- Sentiment analysis powered by **Stocktwits API** and **TextBlob**
