# microsoft-ai-learning

### **Microsoft AI Event Learnings**  

Here is a detailed summary of the topics discussed at the event, focusing on **products**, **technical concepts**, and **developer-centric insights**:  

---

### **Products and Platforms**  

1. **Microsoft AI Foundry (formerly Azure OpenAI Studio)**  
   - A **platform for developing, fine-tuning, and deploying AI models** with tools for prompt engineering and evaluation.  
   - **Features for Developers:**  
     1. Tools for crafting and testing custom prompts.  
     2. Advanced fine-tuning with secure datasets.  
     3. Evaluation (EVAL) tools to measure accuracy and reduce hallucinations.  
     4. Feedback pipelines to iteratively improve model quality.  
     5. Multi-language SDK support for easy integration.  
     6. Integration with Microsoft Purview for governance.  
     7. Detailed cost insights to track token usage effectively.  

2. **Copilot Studio**  
   - A **SaaS platform** for building, deploying, and managing AI copilots tailored for enterprise workflows.  
   - **Features for Developers:**  
     1. Pre-built templates for faster deployment of common use cases.  
     2. Secure integration with Microsoft 365 applications.  
     3. Role-Based Access Control (RBAC) for managing copilots.  
     4. Automation of workflows using event triggers.  
     5. REST APIs for extensibility with third-party systems.  
     6. Scalability to support large organizational deployments.  
     7. Real-time task automation through Copilot Actions.  

3. **Microsoft Fabric**  
   - A **unified data and analytics platform** for integrating real-time data processing, governance, and AI-driven insights.  
   - **Features for Developers:**  
     1. Real-time data ingestion pipelines.  
     2. Lakehouse architecture for unified data management.  
     3. Built-in analytics using Kusto Query Language (KQL).  
     4. Power BI integration for visualization.  
     5. Automation of dataflows and transformations.  
     6. Scalable architecture for structured and unstructured data.  
     7. Security and compliance baked into the platform.

---

### **Use Cases and Examples**  

1. **Copilot Studio:**  
   - Example: Creating a customer service assistant that summarizes tickets, generates responses, and automates escalations.  

2. **AI Foundry:**  
   - Example: Fine-tuning a legal document analysis model to identify risks in contracts.  

3. **Microsoft Fabric:**  
   - Example: Building a real-time dashboard for supply chain monitoring with predictive analytics for delays.  

---

### **Differences: Copilot Studio, AI Foundry, and Microsoft Fabric**  

| **Feature/Aspect**      | **Copilot Studio**                       | **AI Foundry**                      | **Microsoft Fabric**              |
|--------------------------|------------------------------------------|--------------------------------------|------------------------------------|
| **Category**             | SaaS                                    | PaaS                                 | Unified Analytics/Data Platform   |
| **Purpose**              | Build task-specific AI copilots.        | Train and deploy custom AI models.   | Process and analyze real-time data. |
| **Key Focus**            | AI-powered task automation.             | Domain-specific model optimization. | Real-time data intelligence.      |
| **Target Users**         | Business users and developers.          | Developers and data scientists.      | Data engineers and analysts.      |
| **Integration**          | Microsoft 365, Azure Logic Apps.        | Azure ecosystem, OpenAI APIs.        | Power BI, KQL, data lakes.        |
| **Governance Tools**     | Role-based permissions for copilots.    | Purview integration for AI workflows.| Built-in data governance.         |
| **Deployment Model**     | SaaS hosted by Microsoft.               | PaaS customizable on Azure.          | Cloud-native data platform.       |

---

### **Technical Concepts and Frameworks**  

1. **Why We Need an Orchestrator in AI**  
   - Orchestrators manage workflows between AI models, enabling efficient collaboration, prioritization, and scaling in multi-agent systems.  

2. **Model Orchestration**  
   - Refers to managing interactions and dependencies between multiple models or services to ensure efficient task execution in AI applications.  

3. **Agents and Multi-Agent Systems**  
   - Agents are autonomous entities that execute tasks independently. Multi-agent systems involve coordinating these agents to solve complex problems collaboratively.  

4. **OpenAI Function Calling**  
   - Allows AI models to call specific functions in applications, providing structured and controlled execution of tasks.  

5. **Prompty Framework**  
   - A Python library for advanced prompt engineering that helps developers structure and reuse prompts effectively.  

6. **Prompt Injections**  
   - A vulnerability where malicious inputs manipulate AI behavior. Mitigation strategies include input sanitization, sandboxing, and strict prompt rules.  

7. **Reducing Hallucinations with EVAL Support**  
   - Leveraging evaluation tools to test, refine, and validate prompts and model responses to ensure accuracy and reliability.  

8. **Medallion Architecture Pattern**  
   - A data architecture that organizes data into **bronze** (raw), **silver** (cleaned), and **gold** (curated) layers for efficient analytics and AI workflows.  

9. **SLMs (State-of-the-Art Language Models)**  
   - Cutting-edge AI models optimized for scalability, performance, and domain-specific applications, such as GPT-4.  

10. **What is Kernel in AI, and its Role in Inference**  
    - The kernel is a core processing component in AI that enables efficient computation during inference. It works similarly to how GPUs accelerate tasks.  

11. **What is NPU (Neural Processing Unit)?**  
    - A hardware accelerator designed for AI workloads, enabling efficient and high-speed model inference, complementing CPUs and GPUs.  

12. **Token/Dollar Optimization**  
    - Techniques to minimize API costs include optimizing prompts, reducing token usage, and selecting appropriate model configurations.  
13. **Copilot Pages, Actions, and Agents**  
   - **Pages:** Summarize key insights from documents or interactions.  
   - **Actions:** Automate task execution triggered by AI recommendations.  
   - **Agents:** Autonomous assistants embedded in workflows, enabling contextual understanding and task execution.  

14. **Agripolit.AI for Farmers**  
   - A specialized AI tool offering insights for optimizing crop yields, resource management, and weather predictions.  

15. **Microsoft Purview**  
   - A governance platform ensuring secure data management, compliance, and discoverability.  

16. **AI Genius Series**  
   - A developer learning platform providing hands-on experience with Microsoft AI technologies.  

---
