# MultiAgentReporter

An intelligent document summarization system that uses multiple AI agents to create comprehensive reports from any document or topic.

## Overview

MultiAgentReporter employs an orchestrated workflow with multiple AI agents working in parallel to generate structured, comprehensive reports. The system breaks down complex documents into logical sections and assigns specialized AI workers to handle each section concurrently.

## Features

- **Intelligent Planning**: Automatically analyzes input documents and creates a structured report plan
- **Parallel Processing**: Multiple AI agents work simultaneously on different sections
- **Structured Output**: Generates well-formatted markdown reports with clear sections
- **Flexible Input**: Can handle various document types and topics
- **LangGraph Integration**: Uses advanced workflow orchestration for reliable execution

## Architecture

The system consists of three main components:

1. **Orchestrator**: Plans the report structure and sections
2. **Worker Agents**: Individual AI agents that write specific sections
3. **Synthesizer**: Combines all sections into a final coherent report

## Requirements

- Python 3.8+
- OpenAI API key
- LangChain and LangGraph
- Jupyter Notebook environment

## Installation

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
4. Open and run the Jupyter notebook

## Usage

1. Open `MultiAgentReporter.ipynb`
2. Update the `topic` variable with your document or topic
3. Run all cells to generate your report

## Example

The system can generate reports on various topics, such as:
- Technical documentation summaries
- Research paper analysis
- Business report generation
- Educational content organization

## License

MIT License
