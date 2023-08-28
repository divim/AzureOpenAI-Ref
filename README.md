# Azure Qatar Reference for Azure OpenAI workloads
Welcome! This repository serves as a guide for deploying a GPT-powered chat bot to your web application. The reference architecture and guidance complies with Azure Qatar Reference Architecture. 

## Resources
The following resources are available in this repository:

**High Level Diagram**: To highlight the logical flow of Azure components to facilitate conversations with the chat bot on your web application
- ### Dataflow components
  1. **[Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)** is a fully managed service for building, deploying, and scaling web apps. You can build apps by using .NET, .NET Core, Node.js, Java, Python, or PHP. The apps can run in containers or on Windows or Linux. 
In a mainframe migration, the front-end screens or web interface can be coded as HTTP-based REST APIs. They can be segregated as in the mainframe application, and can be stateless to orchestrate a microservices-based system.  In a mainframe migration, the front-end screens or web interface can be coded as HTTP-based REST APIs. They can be segregated as in the mainframe application, and can be stateless to orchestrate a microservices-based system.
  2. **[Azure Api management](https://azure.microsoft.com/en-us/products/api-management/)** :is a managed service that allows you to manage services across hybrid and multi-cloud environments. API management acts as a facade to abstract the backend architecture, which includes APIs for the components critical to the bot. It provides control and security for API observability and consumption.  
  3. **[Azure Functions](https://azure.microsoft.com/en-us/products/functions/)** is an event-driven serverless compute platform. Azure Functions runs on demand and at scale in the cloud.  
  4. **[Azure Open AI](https://azure.microsoft.com/en-us/products/ai-services/openai-service)** is a service that provides AI models that are trained on a large amount of data. You can use these models to generate text, images, and more.
  5. **[Azure Search](https://learn.microsoft.com/en-us/azure/search/)**. Search is a managed service that provides a quick searchable document index. 
  6. **[AKS](https://azure.microsoft.com/en-us/products/kubernetes-service/)**. AKS provides fully managed Kubernetes clusters for deployment, scaling, and management of containerized applications.
  7. **[Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/)** is a fully managed NoSQL and relational database for modern app development.

**Low Level Diagram**: Builds on top of the Azure Qatar Reference Architecture to provide secure and scalable ways to deploy your resources

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
