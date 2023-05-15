[![GitHub Repo stars](https://img.shields.io/github/stars/ruankie/vid-qa)](https://github.com/ruankie/vid-qa)

# 🎥🗨️ VidQA

## Description

VidQA is an AutoGPT app that summarises and answers questions about arbitrary YouTube videos using LangChain and LLMs.

> 🏗️ Under construction. More coming soon...

> 💡 The main idea for this app came from a [YouTube video](https://www.youtube.com/watch?v=NYSWn1ipbgg) by [Dave Ebbelaar](https://www.youtube.com/@daveebbelaar).

## Setup
1. Set up your virtual env with all the required dependencies
    ```shell
    poetry install
    ```
2. Set your environment variables in a file called `.env` (see `.env.example`)
3. [Create a resource and deploy a model using Azure OpenAI](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/how-to/create-resource?pivots=web-portal)

> Note: You can use this directly with OpenAI's API (without using Azure's OpenAI Services) with minor modifications to the code and environment variables

## Usage
> TODO: Add Streamlit app link

> Note: Whe using notebooks, make sure you activate the correct poetry environment. You can set your Python kernel to the value that gets returned when you run `poetry run which python`.

1. Browse the example notebooks in `notebooks/`

## Useful Resources
- https://www.youtube.com/watch?v=NYSWn1ipbgg
- https://platform.openai.com/docs/api-reference
- https://python.langchain.com/en/latest/index.html
