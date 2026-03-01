# Jupyter Notebook Ollama Example

This project demonstrates how to use a Jupyter notebook to call a local Ollama server for LLM inference, with configuration managed by python-dotenv.

## Setup

1. Install dependencies (recommended):
   ```sh
   pip install uv
   uv pip install -r requirements.txt
   ```
   Or, use pip directly if you prefer:
   ```sh
   pip install -r requirements.txt
   ```
2. Update the `.env` file with your Ollama server URL and API key if needed.
3. Start Jupyter:
   ```sh
   jupyter notebook
   ```
4. Open the provided notebook and run the cells.
