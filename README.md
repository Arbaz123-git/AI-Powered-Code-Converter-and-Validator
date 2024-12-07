# AI-Powered-Code-Converter-and-Validator
The above project focuses on validating, converting, and testing small snippets of code in different programming languages using an LLM (Language Learning Model) for assistance. Then writing down the observations and drawing conclusion. 

# AI-Powered Code Converter and Validator

**AI-Powered Code Converter and Validator** is a tool designed to leverage the power of Language Learning Models (LLMs) for converting, validating, and testing code snippets across different programming languages. This repository showcases how AI can assist in tasks like code translation, debugging, and validation with minimal effort.

## Features

- **Code Conversion**: Effortlessly convert code snippets between different programming languages (e.g., Java to Python).
- **Code Validation**: Validate Python code for correctness and identify issues, if any.
- **Code Testing**: Test Python scripts with specific input and verify their functionality.
- **Streaming Output**: Real-time display of generated responses from the LLM.

## Installation

### Prerequisites
- Python 3.8+
- Install the `ctransformers` library for LLM support:
  ```bash
  pip install ctransformers

Model Setup

Download and configure the required model:

Use a supported model like Mistral-7B-Instruct-v0.2-GGUF.
Place the model file (e.g., mistral-7b-instruct-v0.2.Q6_K.gguf) in the appropriate directory.

Usage

Running the Project

Clone the repository

git clone https://github.com/yourusername/AI-Powered-Code-Converter-and-Validator.git
cd AI-Powered-Code-Converter-and-Validator

Modify the code as needed for your specific conversion or validation task.

Run the script:

python main.py

Example Workflow

Convert Java Code to Python:

Provide the Java snippet as input.

Use the LLM to generate the equivalent Python code.

Validate Python Code:

Input Python code to the LLM.

The LLM validates the code and explains any issues.

Test Python Code:

Pass Python scripts with specific inputs to test their functionality.

Outputs are displayed in real-time.


Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request or open an issue.

Acknowledgments

ctransformers library for seamless integration with LLMs.
Mistral-7B-Instruct-v0.2 model for its robust code generation capabilities.
