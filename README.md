# Azure Qatar Reference for Azure OpenAI workloads
Welcome! This repository serves as a guide for deploying a GPT-powered chat bot to your web application. The reference architecture and guidance complies with Azure Qatar Reference Architecture. 

## Resources
The following resources are available in this repository:

- ### High Level Diagram :  
  To highlight the logical flow of Azure components to facilitate conversations with the chat bot on your web application
- ### Low Level Diagram:  
  Builds on top of the Azure Qatar Reference Architecture to provide secure and scalable ways to deploy your resources
- ### Dataflow
  1. action1
  2. action2
  3. action3
  4. action4
  5. action5
  ...
- ### Components
  **User Experience**

    **[Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)** is a fully managed service for building, deploying, and scaling web apps. You can build apps by using .NET, .NET Core, Node.js, Java, Python, or PHP. The apps can run in containers or on Windows or Linux. In a mainframe migration, the front-end screens or web interface can be coded as HTTP-based REST APIs. They can be segregated as in the mainframe application, and can be stateless to orchestrate a microservices-based system.  
   **[PowerBI](https://learn.microsoft.com/en-us/power-apps/)** Used to create monitoring dashboards for your bot.

  **Security and governance**  

    **[Azure Key Vault](https://azure.microsoft.com/en-us/products/key-vault/)** . Store credentials and other secrets using Key Vault.  
    **[Azure Api management](https://azure.microsoft.com/en-us/products/api-management/)** :is a managed service that allows you to manage services across hybrid and multi-cloud environments. API management acts as a facade to abstract the backend architecture, and it provides control and security for API observability and consumption.  

  **Bot cognition and intelligence**  

    **[Azure Functions](https://azure.microsoft.com/en-us/products/functions/)** is an event-driven serverless compute platform. Azure Functions runs on demand and at scale in the cloud.  
    **[Azure Search](https://learn.microsoft.com/en-us/azure/search/)**. Search is a managed service that provides a quick searchable document index.  
    **[Azure Open AI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)** is a service that provides AI models that are trained on a large amount of data. You can use these models to generate text, images, and more.  
    **[Azure Cognitive Services](https://azure.microsoft.com/en-us/products/ai-services)**. provides intelligent algorithms to see, hear, speak, understand, and interpret your user needs by using natural methods of communication.  
    **[AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/)**. AKS provides fully managed Kubernetes clusters for deployment, scaling, and management of containerized applications.  
    **[Azure Container Registry](https://azure.microsoft.com/en-us/products/container-registry/)**. Container Registry is a managed, private Docker registry service on Azure. You can use Container Registry to store private Docker images, which are deployed to the cluster.
    other services...  
  
  **Data ingestion**  

  **Logging and monitoring**    
 **[Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/)** is a fully managed NoSQL and relational database for modern app development.

## Coming soon
A deployment guide and scripts to help you instantly set up these services in your Azure tenant. 

## Contributions
We welcome contributions to enhance and expand this reference architecture. If you have improvements, suggestions, or new insights, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## FAQ
1. **What is GPT?**
GPT (Generative Pre-trained Transformer) is a Large Language Model (LLM) developed by OpenAI. It is a deep learning model based on the Transformer architecture. For more information, refer to [OpenAI](openai.com).
2. **What is the Azure Qatar Reference Architecture**
It is a prescriptive guide for building enterprise-scale architecture to run workloads on Azure in a scalable, secure, and resilient way.
