

# Wolfram Alpha and LangChain Integration

## Overview

This repository demonstrates how to integrate the Wolfram Alpha API and LangChain tools to create a powerful tool for solving mathematical equations and answering questions. It allows you to input mathematical expressions, equations, or questions and retrieve detailed results.

### Features

- Solve mathematical equations.
- Get answers to various types of questions.
- Easily integrate with other LangChain tools.
- Customize the input prompt for specific queries.

## Prerequisites

Before you get started, ensure you have the following prerequisites installed:

- Python: You'll need Python 3.x installed on your system.
- Pip: The Python package manager, pip, is used to install dependencies.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Install the required Python packages using pip:

   ```bash
   pip install wolframalpha
   ```

4. Set up your Wolfram Alpha API key:
   - Sign up for a Wolfram Alpha developer account and obtain an API key.
   - Open `main.py` and set your API key in the following line:

   ```python
   os.environ["WOLFRAM_ALPHA_APPID"] = 'your-api-key'
   ```

## Usage

1. Run the application:

   ```bash
   python main.py
   ```

2. Enter your query when prompted. For example:

   ```plaintext
   Please enter your prompt (e.g., "What is 2x+5 = -3x + 7?"): 
   ```

3. Press Enter, and the program will send the query to the Wolfram Alpha API and display the results.

## Customization

You can customize the input prompt in the `main.py` file. Modify the following line to change the default prompt:

```python
x = input("please enter your prompt for ex :-What is 2x+5 = -3x + 7?")
```

## Credits

- [Wolfram Alpha API](https://products.wolframalpha.com/api/)
- [LangChain](https://github.com/langchain)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to [Mr. Vimal Daga](https://github.com/DIGITALSKYWALKER), [LinuxWorld Information Pvt Ltd](https://www.linuxworldindia.org/), and the LangChain community for inspiration and support.

