# LangchainTest

experimenting with langchain and localai

# Setup

To use ChatGpt set the env OPENAI_API_KEY value and comment out the OPENAI_API_BASE value

To use LocalAi set the OPENAI_API_KEY to any random string and set the OPENAI_API_BASE to http://localhost:8000

Restart the python environment to apply the changes

# Notes

Database queries are working great in LangChain.ipynb when using ChatGpt
When using LocalAi with the gpt4all-j model on my laptop using 4 CPU threads I can get slow basic chat responses but db queries turn int hallucinations and return garbage

# Next Steps

Get a version of localai working with a model that performs better. Maybe by using a GPU and/or different model
