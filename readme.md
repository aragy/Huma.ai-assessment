# Project Setup Instructions

This guide provides steps to set up and run the two notebooks included in this project. The notebooks use Python and several libraries for natural language processing and machine learning tasks.

## Prerequisites

Ensure you have the following installed:

- Python 3.8+
- `pip` for package management
- Virtual environment tool such as `venv` or `conda` (recommended)

## Step 1: Set Up a Virtual Environment (Optional but Recommended)

1. Open a terminal (or Anaconda prompt if using `conda`).
2. Navigate to the project directory:

   ```bash
        cd /path/to/your/project
   ```
3. Create a virtual environment:

    ```bash
        python -m venv venv
    ```
4. Activate the virtual environment:

    ```bash
        source venv/bin/activate     # For Linux/macOS
        .\venv\Scripts\activate       # For Windows
    ```
## Step 2: Install Dependencies

Install the necessary Python packages for the notebooks.

Run the following command to install all required dependencies:

```bash
    pip install pandas pydantic langchain langchain_community langchain_openai langchain_anthropic langchain_google_genai deepeval rank_bm25 faiss-cpu duckduckgo-search
```

