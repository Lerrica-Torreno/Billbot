# Bilbot – Ollama Chatbot

Bilbot is a chatbot built using **Python** and **Ollama**. It is designed to answer questions related to **binary search** and **linear search algorithms**.

The project includes a custom model configuration, chatbot knowledge data, Python logic, and a simple HTML-based user interface.

## Project Overview

Bilbot was created as an educational chatbot that helps users understand searching algorithms.

The chatbot focuses on:

- Binary search
- Linear search
- Differences between search algorithms
- Basic algorithm concepts
- Search-related questions and explanations

## Features

- Answers questions about binary search
- Answers questions about linear search
- Uses a custom Ollama model
- Uses a text file as the chatbot's knowledge source
- Includes a Python-based chatbot program
- Provides a simple web interface
- Designed for educational purposes

## Technologies Used

- Python
- Ollama
- HTML
- CSS
- Large Language Models
- Visual Studio Code
- Git
- GitHub

## Project Files

```text
Ollama-Chatbot-Bilbot/
├── Bilbot-Data.txt
├── Bilbot.py
├── Modelfile
├── index.html
└── README.md

````markdown
# Bilbot – Ollama Chatbot

Bilbot is a chatbot built using **Python** and **Ollama**. It is designed to answer questions related to **binary search** and **linear search algorithms**.

The project includes a custom model configuration, chatbot knowledge data, Python logic, and a simple HTML-based user interface.

## Project Overview

Bilbot was created as an educational chatbot that helps users understand searching algorithms.

The chatbot focuses on:

- Binary search
- Linear search
- Differences between search algorithms
- Basic algorithm concepts
- Search-related questions and explanations

## Features

- Answers questions about binary search
- Answers questions about linear search
- Uses a custom Ollama model
- Uses a text file as the chatbot's knowledge source
- Includes a Python-based chatbot program
- Provides a simple web interface
- Designed for educational purposes

## Technologies Used

- Python
- Ollama
- HTML
- CSS
- Large Language Models
- Visual Studio Code
- Git
- GitHub

## Project Files

```text
Ollama-Chatbot-Bilbot/
├── Bilbot-Data.txt
├── Bilbot.py
├── Modelfile
├── index.html
└── README.md
````

### `Bilbot-Data.txt`

Contains the keywords, information, and training content used by the chatbot.

### `Bilbot.py`

Contains the main Python code responsible for running the chatbot and communicating with the Ollama model.

### `Modelfile`

Contains the configuration and instructions used to create the custom Bilbot model in Ollama.

### `index.html`

Contains the structure and design of the chatbot's web interface.

### `README.md`

Contains the documentation and instructions for the project.

## Prerequisites

Before running the project, make sure the following are installed:

* Python
* Ollama
* A code editor such as Visual Studio Code

Ollama must also be running on your computer before starting the chatbot.

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Ollama-Chatbot-Bilbot.git
```

### 2. Open the Project Folder

```bash
cd Ollama-Chatbot-Bilbot
```

### 3. Create the Bilbot Model

Run the following command inside the project folder:

```bash
ollama create bilbot -f Modelfile
```

This command creates the custom Ollama model using the configuration inside the `Modelfile`.

### 4. Verify the Model

```bash
ollama list
```

Check that the `bilbot` model appears in the list of available Ollama models.

### 5. Install the Required Python Packages

Install the packages required by `Bilbot.py`.

```bash
pip install ollama
```

Additional packages may be required depending on the imports used in the Python file.

### 6. Run the Python Program

```bash
python Bilbot.py
```

### 7. Open the Web Interface

Open the following file in a browser:

```text
index.html
```

You may also use the **Live Server** extension in Visual Studio Code:

1. Open the repository in Visual Studio Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

## Example Questions

Users may ask Bilbot questions such as:

* What is binary search?
* What is linear search?
* What is the difference between binary and linear search?
* When should binary search be used?
* What is the time complexity of linear search?
* Does binary search require sorted data?
* Which search algorithm is faster?

## Purpose of the Project

The purpose of this project is to demonstrate how a locally hosted large language model can be customized to create an educational chatbot.

It also demonstrates the integration of:

* Python programming
* Ollama models
* Custom chatbot data
* Prompt configuration
* A basic web interface

## Limitations

* Bilbot mainly focuses on binary and linear search algorithms.
* The quality of its responses depends on the information provided in the chatbot data and model instructions.
* Ollama must be installed and running locally.
* The chatbot may not answer questions outside its intended topic accurately.
* The project is intended as a basic educational prototype.

## Future Improvements

Possible future improvements include:

* Adding more searching algorithms
* Adding sorting algorithms
* Improving the chatbot interface
* Adding conversation history
* Adding error handling
* Improving response accuracy
* Adding voice input
* Adding mobile responsiveness
* Connecting the HTML interface directly to the Python backend
* Adding more examples and visual explanations

## Author

**Lerrica Jeremy S. Torreno**

## Academic Purpose

This project was created for academic and educational purposes to demonstrate the use of Python, Ollama, and custom language models in building a specialized chatbot.

## Disclaimer

Bilbot is an educational chatbot. Its responses should be reviewed and verified before being used as a primary academic or technical reference.

```

**Suggested GitHub repository description:**

> An educational chatbot built with Python and Ollama that specializes in binary and linear search algorithms.
```

