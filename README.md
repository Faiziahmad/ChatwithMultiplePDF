# Chat with Multiple PDFs Application

## Overview

The Chat with Multiple PDFs application is a user-friendly and robust tool that allows users to interact with the content of multiple PDF documents through a conversational interface. This application leverages advanced PDF processing capabilities and a powerful conversational AI system to provide an intuitive and seamless user experience.

## Features

1. **User-Friendly Interface**: The application offers a clean and intuitive interface, allowing users to easily upload multiple PDF documents and engage in natural conversations.

2. **PDF Text Extraction**: The code efficiently extracts text from uploaded PDFs, making the content accessible for conversation and interaction.

3. **Vector Store and Conversation Chain**: The application utilizes a vector store to efficiently store and retrieve information from multiple PDFs. The conversation chain ensures a coherent and context-aware interaction with the user.

4. **Intelligent Response Generation**: By integrating OpenAI libraries, the application generates intelligent responses to user input, providing a natural and engaging conversation experience.

5. **Streamlit Integration**: The use of Streamlit ensures a seamless and interactive web interface, making it easy for users to navigate and communicate with the application.

## Getting Started

### Prerequisites

- Python 3.x
- Dependencies listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Faiziahmad/chat-with-multiple-pdfs.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
   
3. Change the API Tokens in the .env file

   You can get your API Tokens from OpenAI / HuggingFace Website for free
   ```bash
   https://platform.openai.com/api-keys
   https://huggingface.co/settings/tokens
   ```

5. Run the application:

   ```bash
   streamlit run app.py
   ```

   Access the application in your browser at [http://localhost:8501](http://localhost:8501).

## Usage

1. Upload multiple PDF documents using the provided interface.
2. Engage in conversations with the application by entering text inputs.
3. Experience intelligent responses generated by the AI system based on the content of the PDFs.

## Extensibility and Future Enhancements

The code follows a modular design, allowing for easy extensibility and integration of additional features. Future enhancements could include:

- Support for more document formats.
- Advanced natural language processing features.
- Integration with cloud storage for document accessibility.
- Improved user customization options for conversation preferences.


## Acknowledgments

- The developers acknowledge the contributions of the open-source community and the libraries used in this project.

Feel free to explore, contribute, and use this Chat with Multiple PDFs application to enhance your document interaction experience!
