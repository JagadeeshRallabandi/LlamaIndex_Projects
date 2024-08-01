# Llama Index Projects

This repository contains a collection of projects demonstrating the use of Llama Index for various applications. These projects showcase how to implement Retrieval-Augmented Generation (RAG) using OpenAI API keys and open-source Llama2.

## Projects Included
- Basic RAG using OpenAI API Key
- Basic RAG using Open-Source Llama2

## Setup Instructions

### Prerequisites
- Conda
- Python 3.10

### Steps to Set Up the Environment

1. **Clone the repository:**
    ```bash
    git clone https://github.com/JagadeeshRallabandi/LlamaIndex_Projects.git
    cd LlamaIndex_Projects
    ```

2. **Create a virtual environment:**
    ```bash
    conda create -p venv python==3.10 -y
    ```

3. **Activate the virtual environment:**
    ```bash
    conda activate ./venv
    ```

4. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

### Necessary API Keys

Ensure that you have the necessary API keys and access tokens for the services used in these projects. Create a `.env` file in the root directory of the project and add your keys as follows:

OPENAI_API_KEY=your_openai_api_key
LLAMA2_API_KEY=your_llama2_api_key

### Running the Projects

1. **Navigate to the project directory:**
    ```bash
    cd project-directory
    ```

2. **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```


Happy coding!
