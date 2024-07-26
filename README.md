# README

## Project Overview

This project is a Python-based application that uses the LangChain library to create a sequence of language models for 
problem-solving and decision-making. It uses OpenAI's GPT-3.5-turbo and GPT-4 models to generate solutions, 
evaluate them, deepen the thought process, and rank the solutions.

## Prerequisites

- Python 3.7 or higher
- OpenAI API key

## Installation

1. Clone the repository:

```bash
git clone git@github.com:timpara/TreeOfLLM.git
```

2. Navigate to the project directory:

```bash
cd <project_directory>
```

3. Install the required Python packages:

```bash
poetry install
```

## OpenAI API Key

To use the OpenAI models, you need to have an OpenAI API key. You can obtain this key by creating an account on the [OpenAI website](https://www.openai.com/).

Once you have your API key, you need to set it as an environment variable on your system. The name of the environment variable should be `OPENAI_KEY`.

### Setting the OpenAI API Key as an Environment Variable

#### On Linux:

Open your `.bashrc` or `.zshrc` file (depending on your shell) and add the following line:

```bash
export OPENAI_KEY="your_openai_key"
```

Replace `"your_openai_key"` with your actual OpenAI key. Save the file and source it:

```bash
source ~/.bashrc  # or source ~/.zshrc
```

#### On Windows:

Open the start menu, search for "Environment Variables", and select "Edit the system environment variables". In the System Properties window that appears, click on "Environment Variables". In the Environment Variables window, click on "New" under the "User variables" section and add `OPENAI_KEY` as the variable name and your actual OpenAI key as the variable value.

## Running the Application

To run the application, navigate to the project directory and run the `main.py` script:

```bash
python main.py
```

This will execute the sequence of language models and print the result.

## Contributing

Contributions are welcome. Please submit a pull request or open an issue to discuss the changes you want to make.

## License

This project is licensed under the terms of the MIT license.