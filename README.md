# Text Generation Model for Test Automation

This repository contains sample code based on the article [Implementing AI in Software Testing: Creating a Text Generation Model for Test Automation](https://drlee.io/implementing-ai-in-software-testing-creating-a-text-generation-model-for-test-automation-7294b26f93c4).

## Adding Your OpenAI API Key as a Secret

To use this tool, you'll need to add your OpenAI API Key as a secret in your GitHub repository. Follow these steps:

1. Go to your GitHub repository’s Settings tab.
2. Find the “Secrets” section in the left sidebar and click on “Actions.”
3. Click on “New repository secret.”
4. Name your secret (e.g., OPENAI_API_KEY) and paste your OpenAI API key as the value.
5. Click “Add secret” to save it.

## Setting Up Streamlit Account and Deployment

To deploy the Streamlit app, follow these steps:

1. Create a [streamlit](https://streamlit.io/) account and sign up using your GitHub account.
2. Once logged into Streamlit, click on “New app.”
3. Select the GitHub repository you created earlier.
4. Choose the branch where your files are located (usually main or master).
5. Write `app.py` in the "Path to a Streamlit app" field.
6. In the “Advanced settings,” input your secret key (OPENAI_API_KEY) into the "Environment variables" section.
7. Click “Deploy” to deploy your app. Streamlit will automatically install the dependencies listed in your `requirements.txt` file and deploy your app.
