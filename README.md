# n8n AI Automation Workflows

A collection of hands-on **n8n automation and AI workflows** built while learning workflow automation, API integration, webhooks, AI agents, data processing, error handling, and debugging.

These workflows demonstrate how I use **n8n to connect APIs, automate business processes, and integrate AI into practical workflows**.

## 🚀 Workflows

### 1. n8n101 — Sales Data Pipeline

**Workflow:** `Section 2 - Sales Data Pipeline.json`

A data automation workflow focused on processing sales-related information and building an automated data pipeline.

**Concepts practiced:**

* Data ingestion and transformation
* Workflow automation
* Data processing
* Field mapping
* Connecting multiple workflow nodes
* Building repeatable business automation


Screenshot

<img width="1355" height="604" alt="Sales data Pipeline" src="https://github.com/user-attachments/assets/d156d487-8bc1-486d-8d41-19f3ef018139" />




---

### 2. n8n102 — API & Order Processing Automation

This section contains multiple workflows demonstrating API integration, webhooks, order processing, and reusable sub-workflows.

#### API Integration Pipeline

`Section 1-API Integration Pipe.json`

**Concepts practiced:**

* REST API integration
* HTTP requests
* Request/response handling
* Data transformation
* Connecting external services with n8n

* 

* <img width="1352" height="602" alt="Final Workflow_API Integration" src="https://github.com/user-attachments/assets/397be79e-3f6a-4def-9421-9ea878d68492" />




#### Order Webhook Processor

`Section 2 - Order Webhook Processor.json`

An event-driven workflow that receives order information through a webhook and processes the incoming data.

**Concepts practiced:**

* Webhooks
* Event-driven automation
* JSON data processing
* Workflow branching
* Connecting workflows to downstream processes

<img width="1350" height="592" alt="Webhook Order processor" src="https://github.com/user-attachments/assets/c5c4b943-6a6b-4d24-b8c0-38fd391ef523" />



#### Process Order — Sub-workflow

`Section 2 - Process Order (Sub-workflow).json`

A reusable sub-workflow designed to separate order-processing logic from the main workflow.

**Concepts practiced:**

* Reusable workflows
* Modular automation
* Sub-workflow design
* Passing data between workflows
* Separation of responsibilities

<img width="1356" height="599" alt="Subworkflow" src="https://github.com/user-attachments/assets/37b6b550-ec99-4312-bf06-9780f9a9be73" />


---

### 3. n8n103 — AI & Customer Feedback Automation

This section focuses on integrating **AI into n8n workflows** for customer feedback processing and AI-agent based automation.

#### Customer Feedback AI Pipeline

`Section 1 - Feedback Pipeline.json`

An AI-powered workflow for processing customer feedback and extracting structured information.

The workflow explores:

* AI-based classification
* Sentiment analysis
* Topic identification
* Urgency detection
* Structured AI output
* Automated customer-feedback processing

Screenshot


<img width="1365" height="595" alt="Final Workflow_customer feedback pipeline" src="https://github.com/user-attachments/assets/a39c5580-9d75-4e98-8f69-9d123ff069a7" />


LLM Integration


<img width="1343" height="597" alt="Step8" src="https://github.com/user-attachments/assets/68ba4999-14e3-44d0-a410-cd8dbafb4ac4" />


#### Customer Feedback AI Agent

`Section 1 - Feedback Agent.json`

An AI-agent workflow exploring how an AI agent can process customer requests and interact with workflow tools.

**Concepts practiced:**

* AI agents
* Tool-based AI workflows
* Context management
* Memory
* Structured responses
* Connecting AI agents with automation workflows

* Customer service AI Agent Workflow
  

<img width="1355" height="636" alt="Final Workflow for customer service Agent" src="https://github.com/user-attachments/assets/3731f0cb-479f-4574-a4ea-6781818195f6" />


<img width="1360" height="613" alt="Chat _Tool calling" src="https://github.com/user-attachments/assets/57e0bebd-e232-400f-9dd7-cfa46afd9303" />


<img width="1338" height="601" alt="Test 1_chay" src="https://github.com/user-attachments/assets/8ccd6932-d654-4147-b603-d08ed5edf080" />


AI Chat About enterprise license


<img width="1365" height="659" alt="Enterprise license infor test 3 chat" src="https://github.com/user-attachments/assets/c1fb4528-8ba9-44c2-bffd-6e8c6cb663fe" />

No Information given by AI Agent about other customer


<img width="1347" height="605" alt="No Info about other customer_privacy" src="https://github.com/user-attachments/assets/a809d4c1-942d-462e-9ec7-273a9d10b28a" />


System Diagram

<img width="2816" height="1536" alt="System diagram for workflow" src="https://github.com/user-attachments/assets/ad0b36dd-0f02-42c3-b839-57d4ea62109c" />


---

## 🧠 Key Concepts Learned

Through these workflows, I practiced:

* **n8n workflow automation**
* REST API integration
* Webhooks
* JSON data processing
* Data transformation
* Sub-workflows
* Event-driven automation
* AI agents
* Sentiment analysis
* Text classification
* Topic extraction
* Structured AI outputs
* Workflow debugging
* Error handling
* Connecting AI models with business automation

## 🛠️ Technologies & Tools

* **n8n**
* REST APIs
* Webhooks
* JSON
* AI / LLM integrations
* HTTP APIs
* Workflow automation

## 📂 Repository Structure

```text
n8n-ai-automation-workflows/
│
├── n8n101/
│   └── Section 2 - Sales Data Pipeline.json
│
├── n8n102/
│   ├── Section 1-API Integration Pipe.json
│   ├── Section 2 - Order Webhook Processor.json
│   └── Section 2 - Process Order (Sub-workflow).json
│
├── n8n103 AI course worflows/
│   ├── Section 1 - Feedback Agent.json
│   └── Section 1 - Feedback Pipeline.json
│
└── README.md
```

## ▶️ How to Use

1. Install or open an n8n instance.
2. Clone this repository:

```bash
git clone <your-repository-url>
```

3. Open n8n.
4. Select **Import from File**.
5. Choose any `.json` workflow from this repository.
6. Configure the required credentials and integrations.
7. Review the nodes and connections.
8. Execute the workflow.

> **Note:** Credentials and API keys are not included in this repository. Configure your own credentials inside n8n before executing workflows.

## 🔐 Security

This repository contains exported workflow definitions for learning and portfolio purposes.

Sensitive credentials such as API keys, passwords, access tokens, and secrets should be stored using **n8n credentials/environment variables** rather than hard-coded inside workflow files.

Always review exported workflow JSON before making a repository public.


## 🎯 Purpose

I created these workflows as part of my hands-on learning in **AI automation and agentic AI**.

My goal is to understand not only how to build AI workflows, but also how AI can be combined with APIs, backend systems, data processing, and automation to solve practical problems.

## 📌 Future Improvements

Planned improvements include:

* Adding more AI-agent workflows
* Integrating local LLMs
* Adding RAG-based workflows
* Connecting workflows with backend APIs
* Adding monitoring and error-handling patterns
* Building production-oriented AI automation use cases

---

**Built with n8n • AI • APIs • Automation**
