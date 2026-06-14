# NayePankh Foundation AI Assistant

## About This Project

NayePankh Foundation AI Assistant is a Telegram-based chatbot that I developed to provide information related to NayePankh Foundation. The chatbot can answer questions about internships, volunteer opportunities, foundation activities, and other general information.

I built this project to gain practical experience in Artificial Intelligence, workflow automation, and chatbot development. Instead of only learning concepts from tutorials, I wanted to create a working application that solves a real problem.


## Project Idea

Many users have similar questions about internships, volunteering, and foundation programs. Searching for this information manually can take time. To make the process easier, I developed a chatbot that can respond to user queries directly through Telegram.

The chatbot uses AI to understand questions and generate responses while maintaining conversation context through memory.



## Technologies Used

* n8n
* Groq AI
* Telegram Bot API
* Docker
* AI Agent
* Simple Memory



## How It Works

1. A user sends a message to the Telegram bot.
2. The Telegram Trigger receives the message.
3. The message is sent to an AI Agent created in n8n.
4. The AI model processes the query and generates a response.
5. Memory stores recent conversation history to maintain context.
6. The response is sent back to the user through Telegram.



## Features

* Telegram-based chatbot
* AI-generated responses
* Conversation memory
* Workflow automation using n8n
* Docker-based local setup
* Foundation-specific assistance


## Repository Contents

1.README.md
2.Project-report.pdf
3.NayePankh-Assistant-Workflow.json
4.screenshots/

## Screenshots

Screenshots of the workflow and chatbot interactions are available in the screenshots folder.

## Challenges Faced

While developing this project, I faced challenges related to Telegram integration, workflow configuration, and prompt design. Some responses were initially inconsistent, so I spent time testing different prompts and debugging the workflow until the chatbot behaved as expected.

These challenges helped me improve my understanding of AI workflows and real-world application development.

## What I Learned

Through this project, I learned:

* How AI chatbots are built and connected to external platforms
* Workflow automation using n8n
* Prompt engineering
* Telegram Bot integration
* Docker basics
* Testing and debugging workflows
* Maintaining conversation context using memory

This project gave me practical experience beyond classroom learning and helped me understand how different technologies work together to create a complete application.

## Future Improvements

Some improvements I would like to make in the future include:

* Deploying the chatbot on a public server
* Adding support for multiple languages
* Connecting a knowledge base for more accurate responses
* Creating a web interface for users
* Adding analytics and monitoring features

## Note

This project was developed and tested locally using n8n running inside Docker. Since it is not deployed on a public server, a live demo link is not available. The repository includes the workflow file, project report, and screenshots for demonstration purposes.


## Author

Deepak

B.Tech Computer Science and Engineering

SGT University
