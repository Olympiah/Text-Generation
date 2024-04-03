# Serverless LLM Apps with Amazon Bedrock
To connect AI services like ASR (Automatic Speech Recognition) to your LLM application and also to automate this ML workflow, you can utilize event-driven triggers that will be responsible for running the workflow in realtime. Thereafter, you can deploy the whole workflow so that it can run independently. This saves one the hustle of creating a prototype from scratch and also handling maintenance. 

**Audio summarization use case**

In this project, I connect an LLM to an ASR service **Amazon Transcribe** to enable the LLM to process data that isn't already text eg. call center audio recordings. Also, I connect the service into a workflow that triggers an LLM via AWS lambda to automatically run when new files are uploaded to the S3 bucket(for storage) 

## Steps
* Creating text generations with Amazon Bedrock.
* Summarizing an audio file using transcribe model.
* Logging configurations
* Deploying an AWS lambda function to the cloud.

## Prerequisites

* Python
* Jupyter Notebook
* AWS cloud account



