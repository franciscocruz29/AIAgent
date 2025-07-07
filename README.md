# Project Title
AI Code Assistant

# Description
This project is an AI-powered code assistant that can help you with your codebase. It uses the Gemini API to understand your code and can perform various operations like listing files, reading file content, executing Python scripts, and writing to files.

# Features
*   **AI-powered code understanding:** The agent can understand your code and help you with your requests.
*   **File system operations:** The agent can list files and directories, read file content, and write to files.
*   **Python script execution:** The agent can execute Python scripts with optional arguments.
*   **Extensible:** You can add new functions to the agent to extend its capabilities.

# Installation
1.  Clone the repository:
    ```
    git clone https://github.com/your-username/ai-code-assistant.git
    ```
2.  This project uses [uv](https://github.com/astral-sh/uv) for package management. If you don't have it, you'll need to install it first.
3.  Create a virtual environment and install the dependencies:
    ```
    uv venv
    uv sync
    ```
4.  Set up your environment variables. You'll need to create a `.env` file and add your Gemini API key to it.

# Usage
1.  Activate the virtual environment:
    ```
    source .venv/bin/activate
    ```
2.  To use the AI code assistant, run the `main.py` script with your prompt as an argument:
    ```
    python main.py "your prompt here"
    ```

    For example:
    ```
    python main.py "How do I fix the calculator?"
    ```

    You can also run the script in verbose mode to see the agent's thought process:
    ```
    python main.py "your prompt here" --verbose
    ```