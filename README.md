# KnowItAll - ChatBott
## A Chatbot with Firebase and OpenAI Integration

![Screenshot_20230825_192122](https://github.com/mohammadshahidbeigh/knowitall-ChatBot/assets/85876937/0b1fee88-da6a-423e-9c7c-a4311d921f02)



KnowItAll ChatBot is a web application that seamlessly integrates Firebase Realtime Database with OpenAI's GPT-3.5 Turbo model. Through this integration, the application offers an interactive chatbot experience. The chatbot comprehends user inputs and provides human-like responses, creating a dynamic and engaging conversational interaction. This project demonstrates the integration of Firebase Realtime Database and OpenAI's GPT-3.5 Turbo model to create an interactive chatbot interface. The chatbot responds to user inputs using natural language processing and generates human-like responses.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)


## Prerequisites

Before running the code, you need to have the following prerequisites:

- Node.js and npm installed on your system.
- An OpenAI API key. You can obtain one by signing up on the [OpenAI platform](https://beta.openai.com/signup/).
- A Firebase project with Realtime Database enabled. Obtain the project's database URL.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-chatbot-repo.git

Quick start:

```
$ npm install
$ npm start
```

Head over to https://vitejs.dev/ to learn more about using vite.
## Usage

1. Set up your environment variables:
   
   Create a `.env` file in the root directory of the project and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your_openai_api_key_here
2. Update the Firebase database URL:

In the appSettings object within the index.js file, replace 'your-firebase-database-url' with your Firebase project's database URL

3. Run the application:
    ```
    npm start
    ```
4. Open your web browser and navigate to http://yourlocalhost:Port to interact with the chatbot.

   

## Configuration
To configure the chatbot, consider the following:

Openai: The integration with OpenAI is established using the Openai npm package. The API key is retrieved from the environment variables.


Firebase: The Firebase Realtime Database is used to store and manage conversation data between the user and the chatbot.

Happy Coding!
