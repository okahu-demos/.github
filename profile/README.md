# Okahu demo org
Each repository is a demo for Okahu observability solution. The repository name format is ``okahu-demo-<framework>-<inference-service>``. Please refer to Readme file in every repo for environment setup details. These are all command line chatbot apps that can be run from laptop or Github codespace.

## Additional demos hosted in cloud 
### Azure OpenAI with Azure function demo env
This is a chatbot that answers coffee related questions. It's a RAG design pattern with gpt-3.5-turbo hosted in Azure OpenAI, app code implemented in Llamaindex and deployed in Azure function.
- Client - https://okahuai.postman.co/workspace/Okahu-demo-apps~fa36e930-1373-4418-be26-4f19edb3ebf7/overview
- Azure function - [okahu-demo-bot-az-func](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/WebsitesExtension/Website/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu-demo-rg/providers/Microsoft.Web/sites/okahu-demo-bot-az-func)
- Azure OpenAI resource - [okahu-openai-dev](https://portal.azure.com/#@NETORGFT14510184.onmicrosoft.com/asset/Microsoft_Azure_ProjectOxford/CognitiveServicesAccount/subscriptions/a8215907-de61-45d9-8d3f-aab5a9a432fb/resourceGroups/okahu_rg/providers/Microsoft.CognitiveServices/accounts/okahu-openai-dev)
- API key details in Keeper secrete note -  Azure OpenAI Demo Keys
- Okahu API key stored in the Azure function environment. You need to set to your demo Okahu tenant

### AWS Bederock with AWS Lambda demo env
This is a chatbot that answers coffee related questions. It's a RAG design pattern with gpt-3.5-turbo hosted in AWS Sagemaker, app code implemented in Langchain and deployed in Azure function.
- Client - http://okahu-sagemaker-rag-chatbot-ui.eba-g8fpwhc9.us-east-1.elasticbeanstalk.com/
- Lambda - https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/sagemaker-okahu-demo-langchain
- Sagemaker - https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/studio
- Okahu API key stored in the Azure function environment. You need to set to your demo Okahu tenant
- 
### AWS Sagemaker with AWS Lambda demo env
This is a chatbot that answers coffee related questions. It's a simple LLM inference call with gpt-3.5-turbo hosted in AWS Bedrock, app code implemented in Langchain and deployed in Azure function.
- Client - http://bedrock-kb-chatbot-ui.eba-uvpw32i4.us-east-1.elasticbeanstalk.com/
- Lambda - https://us-east-1.console.aws.amazon.com/lambda/home?region=us-east-1#/functions/bedrock-kb-sbx-ask-question
- Bedrock - https://us-east-1.console.aws.amazon.com/bedrock/home?region=us-east-1#/
- Okahu API key stored in the Azure function environment. You need to set to your demo Okahu tenant<!--
