# Easy Observability for agentic and GenAI apps 

[Okahu](https://www.okahu.ai) is a team of AI, observability & cloud engineers working to simplify observability for agentic and other GenAI apps. We serve AI app developers, platform engineers and engineering leaders to build reliable, accurate and safer AI apps. We believe in community driven open source software and are a major contributor to GenAI native observability [Project Monocle](https://monocle2ai.github.io/docs/) hosted by Linux Foundation.

## Working GenAI apps with observability enabled

We've curated working examples of different kinds of GenAI apps and ways to instrument these apps to get meaningful observability insights. GenAI apps are built using a variety of languages, LLM frameworks, models and cloud services. Instrumentation of these apps is demonstrated using open source including Monocle & OpenTelemetry or commercially supported products from Okahu or friends. 

These examples are aimed at AI app developers, platform engineers or anyone else who want to learn to build and operate impactful GenAI apps. 

## List of demo repositories

| Example | Repository | Description | GenAI app | Observability |
| --- | --- |--- | --- | --- | 
| ![thumbnail]/assets/img/monocle_chatbot_aws.png | [chatbot-coffee-lambda](https://github.com/okahu-demos/chatbot-coffee-lambda) |Cloud hosted interactive chatbot to answer questions about coffee with traces hosted in AWS S3 | TypeScript, Langchain, OpenAI, AWS | Monocle | 


- Refer to readme.md in repo for how to setup environment.
- Most of these demos can be run on your laptop or Github Codespaces. 

## Working demos hosted by Okahu

Okahu team also hosts version of these GenAI apps in our cloud. 

Each repository is a demo for Okahu observability solution. The repository name format is ``okahu-demo-<framework>-<inference-service>``. Please refer to Readme file in every repo for environment setup details. These are all command line chatbot apps that can be run from laptop or Github codespace.

## Additional demos hosted in cloud 
### Azure OpenAI with Azure function demo env
This is a chatbot that answers coffee related questions. It's a RAG design pattern with gpt-3.5-turbo hosted in Azure OpenAI, app code implemented in Llamaindex and deployed in Azure function.
- Client - https://okahuai.postman.co/workspace/Okahu-demo-apps~fa36e930-1373-4418-be26-4f19edb3ebf7/overview
- Azure function - [okahu-demo-bot-az-func](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/WebsitesExtension/Website/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu-demo-rg/providers/Microsoft.Web/sites/okahu-demo-bot-az-func)
- Azure OpenAI resource - [okahu-openai-dev](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/Microsoft_Azure_ProjectOxford/CognitiveServicesAccount/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu_rg/providers/Microsoft.CognitiveServices/accounts/okahu-openai-dev)
- API key details in Keeper secrete note -  Azure OpenAI Demo Keys
- Okahu API key stored in the Azure function environment. You need to set to your demo Okahu tenant

### AWS Bedrock with AWS Lambda demo env
This is a chatbot that answers coffee related questions. It's a RAG design pattern with gpt-3.5-turbo hosted in AWS Sagemaker, app code implemented in Langchain and deployed in Azure function.
- Client - http://okahu-sagemaker-rag-chatbot-ui.eba-g8fpwhc9.us-east-1.elasticbeanstalk.com/
- Lambda - https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/sagemaker-okahu-demo-langchain
- Sagemaker - https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/studio
- Okahu API key stored in the Lambda function environment. You need to set to your demo Okahu tenant

### AWS Sagemaker with AWS Lambda demo env
This is a chatbot that answers coffee related questions. It's a simple LLM inference call with gpt-3.5-turbo hosted in AWS Bedrock, app code implemented in Langchain and deployed in Azure function.
- Client - http://bedrock-kb-chatbot-ui.eba-uvpw32i4.us-east-1.elasticbeanstalk.com/
- Lambda - https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/bedrock-kb-sbx-ask-question
- Bedrock - https://us-east-1.console.aws.amazon.com/bedrock/home?region=us-east-1#/
- Okahu API key stored in the Lambda function environment. You need to set to your demo Okahu tenant<!--
