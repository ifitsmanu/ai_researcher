# AI Researcher

## Overview

AI Researcher is an advanced automation framework designed to streamline the process of gathering, summarizing, and managing information from various online sources. Utilizing a combination of web scraping, natural language processing, and database interactions, this tool is ideal for researchers, data analysts, and anyone looking to efficiently process large amounts of web-based information.

## Features

- **Automated Web Scraping**: Easily extracts content from specified URLs.
- **Content Summarization**: Leverages GPT-3.5 to summarize extracted content.
- **Google Search Integration**: Performs automated searches and retrieves relevant information.
- **Airtable Integration**: Retrieves and updates records in Airtable databases.
- **Multi-Agent System**: Incorporates different AI agents for specialized tasks (e.g., research, data management).
- **User Interaction**: Facilitates user commands and requests via a proxy agent.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Requests library
- BeautifulSoup4
- LangChain
- dotenv for environment variable management

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ifitsmanu/ai_researcher.git 
   ```
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your `.env` file with the necessary API keys:
   - `BROWSERLESS_API_KEY`
   - `SERP_API_KEY`
   - `AIRTABLE_API_KEY`

### Usage

To start the AI Researcher, run the main script:

```bash
python main.py
```

Follow the prompts to input your research query or command.

## Configuration

- Configure API keys and agent settings in the `.env` file.
- Modify agent functions and behaviors in the script as needed.

## Contributing

Contributions to AI Researcher are welcome. Please follow the standard fork-and-pull request workflow.

## License

This project, AI Researcher, is exclusively licensed under The New York Consulting Group. All rights, usage, and distribution are governed by the terms and conditions set forth by The New York Consulting Group.

For more information on the licensing terms or permissions beyond the scope of this license, please contact The New York Consulting Group directly.

# ai_researcher
# ai_researcher
