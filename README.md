# Azure Qatar Reference for Azure OpenAI workloads
Welcome! This repository serves as a guide for deploying a GPT-powered chat bot to your web application. The reference architecture and guidance complies with Azure Qatar Reference Architecture. 

## Resources

### **High Level Diagram**
![High Level Diagram](https://github.com/divim/AzureOpenAI-Ref/blob/main/Logical%20High%20Level%20Diagram.png)
#### DATAFLOWS

**ORANGE**
  1. **[Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)**: Provides a fully managed platform for building and hosting web applications. It is used for hosting in a simple way web applications that consume OpenAI services.
  2. **[Azure Api management](https://azure.microsoft.com/en-us/products/api-management/)** : Provides a unified API gateway for existing back-end services and APIs. It is used in the Landing Zone for managing and securing APIs used by OpenAI applications. APIM can be configured with an Application Gateway as a Web Application Firewall (WAF) to further enhance security. The WAF protects APIs from common web-based attacks like SQL injection or Cross-Site Scripting (XSS) and can be customized to suit specific needs.
  3. **[Azure Functions](https://azure.microsoft.com/en-us/products/functions/)** is an event-driven serverless compute platform. Azure Functions runs on demand and at scale to formulate API calls to Azure OpenAI and other Azure AI services. Additionally, functions can be used to build custom skills and structure data outputs
  4. **[Azure Open AI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)** is a service that provides AI models that are trained on a large amount of data. You can use these models to generate text, images, and more.
  5. **[Azure Search](https://learn.microsoft.com/en-us/azure/search/)**. Search is a managed service that provides a quick searchable document index. 
  6. **[AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/)**. AKS is used to provide Redis as a vector database to provide the functionality forvector similarity search (VSS). The recommended image used for this is "redis-server".
  7. **[Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/)** is a fully managed NoSQL and relational database for modern app development.

**GREEN**
1. **[Azure Data Lake Storage Gen2](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction)**: is a service used to store all the raw data, like pdf, audio, video, and text files.
2. **[Azure Search](https://learn.microsoft.com/en-us/azure/search/)**. Search service is used to index all the raw data. The index can achieved with built-in or custom skills by using Cognitive Services, Azure Open AI and Azure Function.
  
**BLUE**
1. **[Azure Synapse Link for Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/synapse-link)**: Provides native integration between Azure Cosmos DB Analytical Store and Azure Synapse Analytics for the purpose of analyzing data in Cosmos DB.
2. **Azure Spark Pools, Azure Dedicated SQL Pools, Azure AI Language**: Provide a processing and enrichment pipleline during which data is structured and classified to be ready for analysis. Some of the data enrichment capabilities made possible by Azure AI Language are sentiment analysis, key phrase extraction, and text classification. The resulting enriched text will be stored in a Dedicated SQL pool for serving purposes. The processing part can be done in Spark Pools or SQL Pools or even both based on the preference of the developer.
3. **Power BI**: SQL dedicated pools will serve the data to Power BI datasets that will host a semantic model optimized for reporting. Reports can then be developed in Power BI on top of the semantic model to provide the needed insights. Some of which are listed below:
		a. Top searched content
		b. Average session time
		c. Satisfied vs unsatisfied users: Conversations of unsatisfied users can be further analyzed to enhance the whole solution

### **Low Level Diagram**
![Low Level Diagram](https://github.com/divim/AzureOpenAI-Ref/blob/main/Low%20Level%20Diagram.png)
This diagram highlights how to ensure secure deployment of each of the mentioned components through a hub-spoke model of deployment. Please note that there is no public networking enabled for any of the components inside the Azure OpenAI ref. architecture. Private endpoints or VNET integration is leveraged, wherever possible. 

## Contributions
We welcome contributions to enhance and expand this reference architecture. If you have improvements, suggestions, or new insights, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## FAQ
1. **What is GPT?**
GPT (Generative Pre-trained Transformer) is a Large Language Model (LLM) developed by OpenAI. It is a deep learning model based on the Transformer architecture. For more information, refer to [OpenAI](openai.com).
2. **What is the Azure Qatar Reference Architecture**
It is a prescriptive guide for building enterprise-scale architecture to run workloads on Azure in a scalable, secure, and resilient way.
