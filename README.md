# Docling With Ollama

![Project Logo](images/doclingwithollama.png)

## Introduction

Welcome to **Docling with Ollama**! This tool is combines the best of both Docling for document parsing and Ollama for local models. It enables you to use Docling and Ollama for RAG over PDF files (or any other supported file format) with LlamaIndex. It provides you a nice clean Streamlit GUI to chat with your own documents locally.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python**: Make sure you have Python version >3.10 installed. You can download it from [python.org](https://www.python.org/downloads/).
- **Pip**: Ensure pip is installed to manage Python packages. It usually comes with Python.
- **Virtual Environment**: It's recommended to use a virtual environment to manage dependencies. I prefer Conda.
- **Ollama**: Make sure Ollama is installed and llama3.2 model is downloaded with ollama pull llama3.2 command


## Installation

To install **Docling With Ollama**, follow these steps:

1. **Clone the repo**:

    ```bash
    git clone https://github.com/fahdmirza/doclingwithollama
    ```

2. **Navigate to the project directory**:

    ```bash
    cd doclingwithollama
    ```

3. **Create a virtual environment** (recommended):

    Use Conda: (recommended)
    ```bash
      conda create -n ai python=3.11 -y && conda activate ai
    ```
    Or Use Python VENV:
    ```bash
    python3 -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

5. **Install the dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

## Running the Tool

To run **Docling with Ollama**, execute the following command:

```bash
streamlit app.py
```

Open your browser and go to `http://localhost:8501` to see the tool in action, if it doesnt open automatically.

## Usage

From left panel, upload your local PDF file, and start chatting with them.

## Contributing

Contributions are always welcome! See `CONTRIBUTING.md` for ways to get started.

## License

This project is licensed under the APACHE 2.0 License - see the `LICENSE` file for details.

## Contact

For questions or feedback, please contact Fahd Mirza at https://www.youtube.com/@fahdmirza
