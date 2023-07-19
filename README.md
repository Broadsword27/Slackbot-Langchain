
# Slack Chatbot with LangChain

This is a Slack chatbot that uses the LangChain library to provide conversational AI capabilities. The chatbot listens for app_mention events in Slack and generates responses using the LangChain language model.

# Prerequisites

Before running the chatbot, make sure you have the following:

- Python 3.7 or higher installed
- Slack API credentials (bot token and signing secret)
- OpenAI API key
- Environment variables configured in a `.env` file

# Configure environment variables:

Create a .env file in the project directory and add the following variables:
- SLACK_BOT_TOKEN=<your_slack_bot_token>
- SLACK_SIGNING_SECRET=<your_slack_signing_secret>
- OPENAI_API_KEY=<your_openai_api_key>
- SLACK_APP_TOKEN=<your_slack_app_token>


   
