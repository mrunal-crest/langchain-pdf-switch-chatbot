---

# Langchain Chat Bot

## Overview

The Langchain Chat Bot is a Streamlit application that allows users to interact with a conversational AI system trained on document data. Users can select a PDF document, ask questions or provide prompts, and receive responses generated by the AI system based on the content of the selected document.

## Setup

Follow the instructions below to set up and run the project locally:

### Prerequisites

- Python 3.6 or higher installed on your system
- Pip package manager
- Git (optional, for cloning the repository)

### Installation

1. Clone this repository to your local machine using Git:

   ```bash
   git clone https://github.com/your-username/langchain-chat-bot.git
   ```

   Alternatively, you can download the ZIP file and extract it to a local directory.
2. Navigate to the project directory:

   ```bash
   cd langchain-chat-bot
   ```
3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   ```
4. Activate the virtual environment:

   - On Windows:
     ```bash
     env\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source env/bin/activate
     ```
5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

1. Create a `.env` file in the project directory.
2. Add your OpenAI API key to the `.env` file:
   ```
   OPENAI_API_KEY=your-api-key
   ```

### Running the Application

Once the setup is complete, you can run the Streamlit application:

```bash
streamlit run app.py
```

This command will start the Streamlit server and open the application in your default web browser.

### Usage

- Select a PDF document from the sidebar.
- Interact with the chat interface by typing questions or prompts in the input field.
- The chat bot will generate responses based on the content of the selected PDF document.

### Troubleshooting

- If you encounter any issues during setup or while running the application, please refer to the documentation or create a new issue in the repository.

---
