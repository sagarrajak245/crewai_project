# CrewAI Project

## Overview

CrewAI is a framework designed to automate various tasks using specialized agents. In this project, we have created three key agents – **Researcher**, **Writer**, and **Editor** – that work sequentially to search, write, and refine content for various tasks.

### Agents Involved

1. **Researcher**:
   - The **Researcher** agent is responsible for gathering information from various sources. It analyzes the topic and retrieves relevant data to guide the writing process.
   
2. **Writer**:
   - The **Writer** agent uses the insights provided by the Researcher to generate well-structured and coherent content. It ensures the information is presented in a readable format.
   
3. **Editor**:
   - The **Editor** agent reviews the content written by the Writer. It makes necessary corrections, improves the language, checks for grammatical errors, and ensures the content meets the required standards.

### Sequential Workflow

- **Researcher**: Conducts research and provides the data for the Writer.
- **Writer**: Creates content based on the research and hands it over to the Editor.
- **Editor**: Refines the content, ensuring it is polished and ready for final use.

Each agent is designed to handle a specific task, making the workflow efficient and organized. The system follows a sequential order where tasks are passed from one agent to the next.

## Features

- **Automated Research**: The Researcher agent gathers detailed information on the given topic.
- **Content Creation**: The Writer agent generates high-quality text based on research.
- **Content Editing**: The Editor agent refines the content for correctness and clarity.

## Installation

To set up the CrewAI project, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/sagarrajak245/crewai-project.git
   pip install -r requirements.txt

