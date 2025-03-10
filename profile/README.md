# Easy Observability for agentic and GenAI apps 

[Okahu](https://www.okahu.ai) is a team of AI, observability & cloud engineers working to simplify observability for agentic and other GenAI apps. We serve AI app developers, platform engineers and engineering leaders to build reliable, accurate and safer AI apps. We believe in community driven open source software and are a major contributor to GenAI native observability [Project Monocle](https://monocle2ai.github.io/docs/) hosted by Linux Foundation.

## Working GenAI apps with observability enabled

We've curated working examples of different kinds of GenAI apps and ways to instrument these apps to get meaningful observability insights. GenAI apps are built using a variety of languages, LLM frameworks, models and cloud services. Instrumentation of these apps is demonstrated using open source including Monocle & OpenTelemetry or commercially supported products from Okahu or friends. 

These examples are aimed at AI app developers, platform engineers or anyone else who want to learn to build and operate impactful GenAI apps. 

## List of demo repositories

| Example | Repository | Description | GenAI app | Observability |
| --- | --- |--- | --- | --- | 
| <img src="monocle_chatbot_aws.png" width="480"> | [chatbot-coffee-lambda](https://github.com/okahu-demos/chatbot-coffee-lambda) |Cloud hosted interactive chatbot webapp to answer questions about coffee with traces hosted in AWS S3 | Next.js, TypeScript + Python, Langchain, OpenAI, AWS | Monocle | 
| <img src="monocle-chat-vercel.png" width="480">| [chatbot-coffee-vercel](https://github.com/okahu-demos/chatbot-coffee-vercel) |Vercel hosted interactive chatbot webapp to answer questions about coffee with traces hosted in AWS S3 | Next.js, TypeScript, Langchain, OpenAI, Vercel | Monocle | 
| --- | [okahu-demo-lc-openai](https://github.com/okahu-demos/okahu-demo-lc-openai) |Personal interactive chatbot command line python app to answer questions about coffee with local traces. Runs on your laptop or Github Codespaces  | Python, Langchain, OpenAI, Github Codespaces/Laptop | Okahu | 

## Working demos hosted by Okahu

Okahu team also hosts version of these GenAI apps in our cloud.[^1]  

| Demo | Instructions | Observability | 
| -- | -- | -- | 
|<img src="ai-assistant-vercel.png" width="480"> | AI assistant that answers questions about coffee to demo instrumentation of GenAI apps with open-source Monocle. <br> [Ask a question](https://chatbot-coffee-vercel.vercel.app/) and [View Monocle generated traces](https://chatbot-coffee-vercel.vercel.app/s3) | Monocle | 
|<img src="ai-assistant-aws.png" width="480">| Interactive chatbot webapp that answers questions about coffee hosted in AWS with Monocle traces pushed to S3. <br> <img src="Typescript.svg" width="16"> [Ask a question](https://monocle2ai.okahu.io) and [View Monocle generated traces](https://monocle2ai.okahu.io/s3) <br> <img src="Python.svg" width="16"> [Ask a question](https://monocle2ai-py.okahu.io) and [View Monocle generated traces](https://monocle2ai-py.okahu.io/s3) | Monocle | 
|<img src="rag-in-azure.png" width="480">| REST based chatbot that answers coffee related questions. <br> Follows a RAG design pattern with gpt-3.5-turbo hosted in Azure OpenAI, app code implemented in Llamaindex and deployed in Azure function. <br> 1. Postman [Client](https://okahuai.postman.co/workspace/Okahu-demo-apps~fa36e930-1373-4418-be26-4f19edb3ebf7/overview)   <br>2.  Azure Functions [okahu-demo-bot-az-func](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/WebsitesExtension/Website/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu-demo-rg/providers/Microsoft.Web/sites/okahu-demo-bot-az-func)   <br>3. Azure OpenAI [okahu-openai-dev](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/Microsoft_Azure_ProjectOxford/CognitiveServicesAccount/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu_rg/providers/Microsoft.CognitiveServices/accounts/okahu-openai-dev)   <br>4. Okahu Cloud [Personal](https://portal.okahu.ai) | Okahu | 
|<img src="LLM-in-AWS.png" width="480">| REST based chatbot that answers coffee related questions. <br> Simple app with an LLM inference call to gpt-3.5-turbo hosted in AWS Bedrock from a Langchain apps served in AWS Lambda. <br> 1. [Client](http://bedrock-kb-chatbot-ui.eba-uvpw32i4.us-east-1.elasticbeanstalk.com/)  <br>2. AWS Lambda [function bedrock-kb-sbx-ask-question](https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/bedrock-kb-sbx-ask-question) <br>3. AWS [Bedrock](https://us-east-1.console.aws.amazon.com/bedrock/home?region=us-east-1#/) <br>4. Okahu Cloud [Personal](https://portal.okahu.ai) | Okahu | 
|<img src="rag-in-aws.png" width="480">| REST based chatbot that answers coffee related questions. <br> Follows a RAG design pattern with gpt-3.5-turbo hosted in Sagemaker, app code implemented in Langchain and deployed in AWS Lambda function.  <br> 1. Client [okahu-sagemaker-rag-chatbot-ui](http://okahu-sagemaker-rag-chatbot-ui.eba-g8fpwhc9.us-east-1.elasticbeanstalk.com/)  <br> 2. AWS Lambda [function sagemaker-okahu-demo-langchain](https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/sagemaker-okahu-demo-langchain) <br> 3. AWS Sagemaker [Studio](https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/studio) <br> 4. Okahu Cloud [Personal](https://portal.okahu.ai) | Okahu |

## Contribute 

Email dx@okahu.ai to contribute your demo apps to this repo. 

[^1]: Use of Okahu hosted demo is covered by Okahu's [terms of service for evaluations](https://www.okahu.ai/agreements/evaluation-agreement). 
  [Okahu](https://www.okahu.ai) is a team of AI, observability & cloud engineers working to simplify observability for agentic and other GenAI apps. We serve AI app developers, platform engineers and engineering leaders to build reliable, accurate and safer AI apps. We believe in community driven open source software and are a major contributor to GenAI native observability Project Monocle hosted by Linux Foundation.
  Connect with us on [Linkedin](https://www.linkedin.com/company/99272699/admin/dashboard/), [Github](https://github.com/okahu) or email us at <dx@okahu.ai>


