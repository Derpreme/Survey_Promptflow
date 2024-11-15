# Student-Echo PromptFlow Pipeline

## Overview

This repository contains the source code for the **Student-Echo PromptFlow Project**, an advanced pipeline leveraging **Azure AI** to enable seamless integration of **Large Language Models (LLMs)** and survey data analysis. The pipeline is designed to process **survey response data** using **state-of-the-art LLMs** such as **GPT-4.0** and **Llama3**, and integrates with **MySQL databases** for efficient data management.

### Key Features

1. **Data Retrieval**: Connects to a **MySQL database** to retrieve raw survey response data efficiently.
2. **LLM Integration**: Leverages cutting-edge **LLMs (GPT-4.0 and Llama3)** for sentiment analysis, natural language understanding, and advanced text processing.
3. **Result Storage**: Outputs processed data and stores results back into the **MySQL database**, ensuring a complete **end-to-end data pipeline**.
4. **Azure AI PromptFlow**: Utilizes the **Azure AI PromptFlow Platform** for orchestrating prompts, managing workflows, and optimizing LLM-based analyses.

## Repository Structure

- **`src/`**: Source code for connecting to MySQL, LLMs, and orchestrating prompt flows.
- **`config/`**: Configuration files for database connection, LLM settings, and Azure PromptFlow integration.
- **`templates/`**: Jinja2 templates for prompt engineering and dynamic text generation.
- **`results/`**: Processed outputs and analyses stored in structured formats.

## Key Technologies and Tools

- **Large Language Models (LLMs)**: GPT-4.0, Llama3.
- **Azure AI PromptFlow**: For workflow orchestration and prompt engineering.
- **Python**: Core programming language for data engineering, LLM interaction, and database operations.
- **MySQL**: Relational database for storing and retrieving survey response data.
- **Jinja2**: For dynamic prompt engineering and template-based text generation.
- **ETL Pipelines**: End-to-end workflows for data extraction, transformation, and loading.

## Installation and Setup

### Prerequisites
- **Python 3.9+**
- **Azure AI Account** with PromptFlow enabled.
- **MySQL Server

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-echo-promptflow.git
   cd student-echo-promptflow 

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   
3. Configure database and Azure credentials in config/settings.json.

4. Run the pipeline
    ```bash
    python src/main.py

## Applications
- Sentiment Analysis: Extracting actionable insights from survey data.
- Natural Language Understanding: Gaining a deeper understanding of open-ended survey responses.
- AI-Driven Data Processing: Utilizing LLMs for text-based analytics.
- Educational Insights: Supporting Student-Echo in amplifying student voices through data-driven AI solutions.

## Skills Demonstrated
- AI Engineering: Designing and deploying LLM-based AI solutions using Azure AI.
- Data Science: Analyzing text data with cutting-edge natural language processing (NLP) techniques.
- Database Management: Integrating and operating on large-scale data using MySQL.
- Cloud Computing: Leveraging Azure for scalable and reliable AI workflows.
- Software Engineering: Building efficient, modular, and production-ready pipelines.

## Future Enhancements
- Add support for additional LLMs (e.g., OpenAI models, Google Gemini).
- Implement real-time analytics for immediate survey response processing.
- Extend pipeline to support other database systems (e.g., PostgreSQL, MongoDB).
- Enhance prompt engineering techniques for improved LLM performance.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes. Ensure your code is well-documented and follows the repository’s coding standards.

## Contact
For inquiries or further information, feel free to contact:

Andrew Li: LAndrewi@hotmail.com 



