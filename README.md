# 🚀 Get Started

**This repo is where attendees go to continue their learning after your session — and your Copilot agent will help you set it up.**

### Step 1: Open your repo

Open this repo in a **Codespace** (click the green **Code** button → **Create a Codespace**) — or clone it locally. Then open **GitHub Copilot Chat**.

### Step 2: Add your content

Give the agent something to work with. Drag files into the Explorer panel — session abstracts, outlines, screenshots, notes — and drop them in one of two places:

| Where to put it | What goes there | Who sees it |
|---|---|---|
| **`_remove-before-publish/`** | Internal reference materials (abstracts, outlines, screenshots, planning docs) | **Copilot only** — never published |
| **`/docs/`, `/src/`, or repo root** | Lab instructions, demo code, sample data, getting-started guides | **Attendees** — published with the repo |

> 💡 Not sure? Start by dropping your session abstract or outline into `_remove-before-publish/`. The agent will figure out what to do with it.

### Step 3: Ask the Agent

Once your content is in the repo, use these three phrases with Copilot to build out your session repo:

| Phrase to use with Copilot | What it does | When to run it |
|---|---|---|
| **"Help me get started"** | Sets up session title, description, outcomes, and owners | After you've added your session abstract or outline to the repo |
| **"Help me refine content"** | Organizes your session content into the repo | Each time you add or update content |
| **"Help me finalize"** | Final review, cleanup, and publication prep | When you're ready to publish |

> 💡 **These three phrases are just the starting point.** Copilot can do much more — try asking it to brainstorm next steps for attendees, generate code samples, or build out your repo structure. Don't be afraid to put it in plan mode and ask for what you need.

---

<a name="start-building"></a>
<br>
<p align="center">
<img src="img/banner-build-26.png" alt="Microsoft Build 2026" width="1200"/>
</p>

# [Microsoft Build 2026](https://build.microsoft.com)

## 🔥 BRK224: PepsiCo's blueprint for agentic AI

### Session Description

Learn from Microsoft and PepsiCo engineers who modernized PepsiCo's data foundation for agentic applications using Azure SQL, Cosmos DB, PostgreSQL, and Azure Databricks. Discover a practical build path for agentic RAG architecture, leveraging Azure SQL features like vector indexing and semantic search, to streamline app development and enable faster, repeatable patterns. Refresh your own data layer to reduce app development cycles while leveraging modern, repeatable patterns to ship faster.

### 🧠 Learning Outcomes

By the end of this session, you will be able to:

- Design an enterprise data foundation for agentic AI using Azure Databricks, Azure Cosmos DB, and Azure SQL.
- Apply Azure SQL capabilities, including vector indexing and semantic search, to implement practical RAG patterns for AI agents.
- Build and operationalize AI agent workflows with Microsoft Foundry by connecting agents to modern data platforms for repeatable delivery.

### 💬 Keep Learning with Copilot

Try these prompts with GitHub Copilot to explore the topics from this session. Open Copilot Chat in VS Code (`Ctrl+Alt+I` on Windows/Linux, `Cmd+Shift+I` on Mac), paste a prompt, and see what you learn. Try connecting the [Microsoft Learn MCP Server](#-microsoft-learn-mcp-server) for the latest official documentation.

Use these as a starting point — or write your own!

- "Design a reference architecture for an agentic RAG solution using Azure Databricks, Azure Cosmos DB, and Azure SQL. Explain why each service is used."
- "Show me an Azure SQL example for vector indexing and semantic search, and explain how it improves retrieval quality for AI agents."
- "Compare when to store data in Azure Cosmos DB versus Azure SQL for an AI agent application that needs transactional data and knowledge retrieval."
- "Create a step-by-step plan to operationalize an AI agent in Microsoft Foundry, including evaluation, monitoring, and iteration."
- "Generate an end-to-end sample workflow where an AI agent uses Azure SQL for retrieval and Cosmos DB for operational state."
- "List common anti-patterns in enterprise agentic AI data architectures and how to avoid them using Databricks, Cosmos DB, Azure SQL, and Foundry."

### 💻 Technologies Used

1. Azure Databricks
1. Azure Cosmos DB
1. Azure SQL
1. Microsoft Foundry
1. AI Agents

### 📚 Resources and Next Steps

The source code for the customer application is not publicly available, per the customer's IP requirements. Use the following resources to learn more:

| Resource | Description |
|:---------|:------------|
| [Budget Bytes Samples](https://github.com/Azure-Samples/budget-bytes-samples) | Sample application patterns for Azure SQL and related data architecture concepts. |
| [Azure SQL DB Vector Search](https://github.com/Azure-Samples/azure-sql-db-vector-search) | End-to-end samples for vector search patterns in Azure SQL and SQL Server. |
| [Cosmos DB RAG Chat (ACA)](https://github.com/Azure-Samples/cosmos-db-rag-chat-aca) | Containerized RAG chat sample using Azure Cosmos DB hybrid vector search. |
| [Azure SQL + Databricks Samples](https://github.com/Azure-Samples/azure-sql-db-databricks) | Integration samples and best practices for Azure SQL and Azure Databricks. |
| [Get Started with AI Agents](https://github.com/Azure-Samples/get-started-with-ai-agents) | Foundational Azure AI Foundry agent sample for building and deploying agent apps. |
| [AI Foundry Agents Samples](https://github.com/Azure-Samples/ai-foundry-agents-samples) | Focused code samples for Azure AI Foundry agent development patterns. |
| [Foundry Hosted Agent Framework Demos](https://github.com/Azure-Samples/foundry-hosted-agentframework-demos) | Practical demos for deploying Agent Framework solutions to Foundry Hosted Agents. |
| [https://aka.ms/build26-next-steps](https://aka.ms/build26-next-steps) | Explore lab and session repos to further your learning from Microsoft Build |


### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the products and services covered in this session.

**VS Code** — One click installation: 

[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)


**GitHub Copilot CLI** — Run this to install the Learn MCP Server as a plugin:
```
/plugin install microsoftdocs/mcp
```

For more info, other clients, and to post questions, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

## Content Owners

<table>
<tr>
    <td align="center"><a href="https://github.com/rgward">
        <img src="https://github.com/rgward.png" width="100px;" alt="Bob Ward"/><br />
        <sub><b>Bob Ward</b></sub></a><br />
            <a href="mailto:bobward@microsoft.com" title="email">bobward@microsoft.com</a>
    </td>
</tr></table>

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
