# Llama2 Model API

## Overview
This is a FastAPI application that serves as an API endpoint for the Llama2 model. The API allows users to get answers from the Llama2 model.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/metriccoders/chatgpt_llama2_backend.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chatgpt_llama2_backend
    ```
## Usage
1. Install all the required dependencies: llama_cpp, fastapi, uvicorn and pydantic.
2. Download the Llama2.gguf model from https://huggingface.co/TheBloke/Llama-2-7B-GGUF/tree/main
3. Start the server:
    ```bash
    uvicorn main:app --reload
    ```
## License
MIT
