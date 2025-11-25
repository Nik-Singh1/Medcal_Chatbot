# Medical Chatbot

A conversational AI chatbot designed to provide medical information and assistance using advanced language models.

## Project Overview

This project implements an intelligent medical chatbot that can interact with users to answer health-related questions and provide informative responses. The chatbot leverages language models and prompt engineering to deliver accurate and helpful medical information.

## Project Structure

```
.
├── app.py                 # Main application entry point
├── requirements.txt       # Python dependencies
├── setup.py              # Package setup configuration
├── template.sh           # Shell template script
├── README.md             # Project documentation
├── LICENSE               # Project license
├── src/
│   ├── __init__.py       # Package initialization
│   ├── helper.py         # Utility helper functions
│   └── prompt.py         # Prompt engineering and templates
└── research/
    └── trails.ipynb      # Research and experimentation notebook
```

## Prerequisites

- Python 3.8 or higher
- Conda (Anaconda/Miniconda)
- Git

## Installation

### Step 01 - Create a Conda Environment

After opening the repository, create a dedicated conda environment:

```bash
# Create a new conda environment
conda create -n medcal_chatbot python=3.9

# Activate the environment
conda activate medcal_chatbot
```

### Step 02 - Install Dependencies

Install the required packages:

```bash
# Install dependencies from requirements.txt
pip install -r requirements.txt
```

### Step 03 - Configure Environment Variables

Create a `.env` file in the project root with necessary API keys and configuration:

```bash
# Example .env file
API_KEY=your_api_key_here
MODEL_NAME=your_model_name
```

## Project Files

### Main Application
- **app.py**: Entry point for running the chatbot application

### Source Code (`src/`)
- **helper.py**: Contains utility functions for the chatbot operations
- **prompt.py**: Manages prompt templates and engineering for medical responses

### Research
- **research/trails.ipynb**: Jupyter notebook for experimentation and research

## Usage

### Running the Application

```bash
# Make sure the conda environment is activated
conda activate medcal_chatbot

# Run the application
python app.py
```

## Features

- Interactive conversational interface
- Medical knowledge base integration
- Prompt engineering for accurate responses
- Helper utilities for common operations
- Extensible architecture for future enhancements

## Development

### Adding New Features

1. Create utility functions in `src/helper.py`
2. Define new prompts in `src/prompt.py`
3. Integrate into `app.py`

### Running Experiments

Use `research/trails.ipynb` for testing and experimentation with new features.

## Dependencies

All dependencies are listed in `requirements.txt`. Key dependencies typically include:
- Language model libraries (LLM frameworks)
- Natural language processing tools
- Web frameworks (if applicable)
- Utility libraries

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Repository

Project repository: https://github.com/Nik-Singh1/Medcal_Chatbot

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bug reports and feature requests.

## Support

For questions or issues, please open an issue in the repository or contact the maintainers.
