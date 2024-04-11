# Langchain-LLM-Demo

## Overview
This repository contains a Streamlit application demonstrating the use of Langchain with the LLAMA2 model to create an interactive Q&A interface.

## Features
- Integration of Langchain with LLAMA2 model for natural language processing.
- Implementation of a Streamlit web interface for real-time user interaction.
- Use of environment variables for secure API key management.

## Getting Started
1. **Clone the repository:**
2. **Set up the environment:**
- Ensure you have Python installed on your machine.
- Install the required Python packages using the command:
  ```
  pip install streamlit langchain-openai dotenv
  ```
3. **Configuration:**
- Create a `.env` file in the root directory.
- Add your Langchain API key to the `.env` file:
  ```
  LANGCHAIN_API_KEY=your_api_key_here
  ```
- In terminal - `export LANGCHAIN_API_KEY='your key'`

## Running the Application
- In terminal - `streamlit run localama.py`

## License
This project is open-sourced under the MIT license. See the LICENSE file for more details.
