# Azure Qatar Reference for Azure OpenAI workloads
Welcome! This repository serves as a guide for deploying a GPT-powered chat bot to your web application. The reference architecture and guidance complies with Azure Qatar Reference Architecture. 

## Resources
The following resources are available in this repository:

- **High Level Diagram**: To highlight the logical flow of Azure components to facilitate conversations with the chat bot on your web application
- **Low Level Diagram**: Builds on top of the Azure Qatar Reference Architecture to provide secure and scalable ways to deploy your resources
- **Dataflow**
  1. action1
  2. action2
  3. action3
  4. action4
  5. action5
  ...
- **Components**
  
  **[Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)** is a fully managed service for building, deploying, and scaling web apps. You can build apps by using .NET, .NET Core, Node.js, Java, Python, or PHP. The apps can run in containers or on Windows or Linux. In a mainframe migration, the front-end screens or web interface can be coded as HTTP-based REST APIs. They can be segregated as in the mainframe application, and can be stateless to orchestrate a microservices-based system.  

 Azure App service considerations & recommendations are broken down into six different design areas, where you can find the links to each at:
| Design Area|Considerations|Recommendations|
|--------------|--------------|--------------|
| Identity and Access Management|[Design Considerations](/docs/Design-Areas/identity-access-mgmt.md#design-considerations)|[Design Recommendations](/docs/Design-Areas/identity-access-mgmt.md#design-recommendations)|
| Network Topology and Connectivity|[Design Considerations](/docs/Design-Areas/networking.md#design-considerations)|[Design Recommendations](/docs/Design-Areas/networking.md#design-recommendations)|
| Management and Monitoring|[Design Considerations](/docs/Design-Areas/mgmt-monitoring.md#design-consideration)|[Design Recommendations](/docs/Design-Areas/mgmt-monitoring.md#design-recommendation)|
| Business Continuity and Disaster Recovery|[Design Considerations](/docs/Design-Areas/BCDR.md#design-considerations)|[Design Recommendations](/docs/Design-Areas/BCDR.md#design-recommendations)|
| Security, Governance, and Compliance|[Design Considerations](/docs/Design-Areas/security-governance-compliance.md#design-considerations)|[Design Recommendations](/docs/Design-Areas/security-governance-compliance.md#design-recommendations)|
| Application Automation and DevOps|[Design Considerations](/docs/Design-Areas/automation-devops.md#design-considerations)|[Design Recommendations](/docs/Design-Areas/automation-devops.md#design-recommendations)|

  
  **[Azure Functions](https://azure.microsoft.com/en-us/products/functions/)** is an event-driven serverless compute platform. Azure Functions runs on demand and at scale in the cloud.
  
  **[Azure Api management](https://azure.microsoft.com/en-us/products/api-management/)** :is a managed service that allows you to manage services across hybrid and multi-cloud environments. API management acts as a facade to abstract the backend architecture, and it provides control and security for API observability and consumption.  
Azure API management considerations & recommendations are broken down into six different design areas, where you can find the links to each at:
  
| Design Area|Considerations|Recommendations|
|:--------------:|:--------------:|:--------------:|
| Identity and Access Management|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/identity-and-access-management#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/identity-and-access-management#design-recommendations)|
| Network Topology and Connectivity|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/network-topology-and-connectivity#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/network-topology-and-connectivity#design-recommendations)|
| Security|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/security#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/security#design-recommendations)|
| Management|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/management#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/management#design-recommendation)|
| Governance|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/governance#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/governance#design-recommendations)|
| Platform Automation and DevOps|[Design Considerations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/platform-automation-and-devops#design-considerations)|[Design Recommendations](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/api-management/platform-automation-and-devops#design-recommendations)|


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
