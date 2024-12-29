# SpokenGPT
Cloud API-based speaking practice application

[中文](https://github.com/nobinobita76/SpokenGPT/blob/main/readme_cn.md)

## Overview

SpokenGPT is a cloud API-based speaking practice application that integrates speech recognition, conversational AI, and text-to-speech APIs to create an interactive learning environment for improving spoken language skills. Utilizing advanced prompt engineering techniques, SpokenGPT offers features like difficulty adjustment, topic guidance, and error correction scoring within a conversational context.

## Features

### Implemented Functions

- **Speech Recognition**: Converts spoken language into text for processing.
- **Conversational AI (GPT)**: Engages in natural language conversations, providing a responsive and interactive experience.
- **Text-to-Speech Synthesis**: Converts text responses back into spoken language.
- **Web Interaction Page**: A user-friendly interface for interacting with the application.
- **Prompt Engineering**: Utilizes ChatGPT's capabilities to:
  - Provide error correction and scoring.
  - Adjust the difficulty level of conversations.
  - Guide topics within discussions.

### Conversation Modes

SpokenGPT offers two distinct modes for conversation practice:

- **Daily Communication Practice**:
  - A relaxed and free-flowing exchange.
  - Adjustable difficulty levels for tailored practice.
  - Offers accent and grammar scoring to help users improve their speech.

- **IELTS Speaking Test Simulation**:
  - Strictly follows the exam, adhering to the official structure.
  - Uses the latest question bank from May to August 2023 for topical practice.
  - Provides feedback on the coherence, accuracy, and lexical resource of individual responses.
  - Offers better response examples provided by GPT for comparison and learning.

## Getting Started

To get started with SpokenGPT, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/nobinobita76/SpokenGPT.git
   ```

2. **Set Up Environment**: Ensure you have the necessary APIs and dependencies installed.
   
   ChatGPT API and Azure API.

   Configure Settings: Adjust the settings according to your needs, including API keys and environment variables.

4. **Run the Application**: Start the application and begin practicing your speaking skills.
   ```bash
   pip install -r requirements
   ```
   and run backend app. (Python Flask)
   ```bash
   npm install
   ```
   and run frontend app. (Vue)
   
   Backend App has been built as `dist\`, you can just run app.py to run the entire app.
   ```bash
   python app.py
   ```
  #### Frinedly Link
  [FileReaderAssistant](https://gitee.com/juventus_bupt/file-reader-assistant) 
