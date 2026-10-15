<a name="start-building"></a>

<p align="center">
<img src="img/banner-frontier-tour-27.png" alt="Microsoft Frontier Tour 2027" width="100%"/>
</p>

# [Microsoft Frontier Tour 2027](https://aitour.microsoft.com)

## 🔥 ILL392: Build agentic AI Postgres apps on Azure HorizonDB

### Session description

How can you ship agentic apps fast if your data layer keeps fragmenting? Learn how to build an agentic app with Azure HorizonDB (Postgres) as your relational store, full-text search engine, vector database, graph database, and long-term memory store for the agent.

### 🚀 Getting started

#### In a guided session

If you're following along during a live session:

1. Open the lab environment and sign in with the provided credentials.
2. Follow the setup guidance in [`instructions/README.md`](instructions/README.md)
3. Open and follow the exercises in the [`instructions/`](instructions/) folder.

#### On your own

If you're learning at your own pace at home:

1. Clone this repository
2. Set up your environment by following the steps in [the self deployment guide](setup/SETUP.md)
3. Follow the session guidance in [`instructions/`](instructions/README.md), then work through the 2 notebooks in the [`src/`](/src/) folder sequentially.

### 🎯 Learning outcomes

By the end of this session, you will be able to:

- Create a Postgres database serving relational, vector, full-text, and graph queries.
- Load a dataset and enable extensions inside HorizonDB.
- Assemble a Microsoft Agent Framework agent employing BM25 keyword search, vector similarity (DiskANN), citation-graph traversal (Apache AGE), in-database entity extraction (`azure_ai`), and an external weather API.

### 💻 Technologies used

- Azure HorizonDB with rich AI extension surface (`vector`, `pg_textsearch`, `age`, `pg_diskann`, `azure_ai`)
- Microsoft Agent Framework
- Apache AGE
- Azure OpenAI
- Mem0
- Gradio
- Python and Jupyter notebooks (driven by `psycopg`, `openai`, `agent-framework`, `mem0`, `gradio`)
- External weather API

### 📚 Continue your learning

Pick your next step based on your learning style:

| Resource | What you'll get |
|----------|-----------------|
| **[Session Recording](https://aka.ms/ft27/ill392/youtube)** | A recording of session ILL392 by the session creator |
| **[Microsoft Learn](https://learn.microsoft.com)** | Official documentation and guided learning paths on these topics |
| **[Frontier Tour 2027 Resource Center](https://aka.ms/FrontierTour27)** | Additional session repos and materials from Frontier Tour 2027 |
| **[Agentic Advisor Solution Accelerator](https://aka.ms/agentic-advisor)** | Pre-built solution accelerator for building agentic AI applications |
| **[GraphRAG solution for Azure Database for PostgreSQL](https://aka.ms/pg-graphrag)** | An end-to-end example of applying the GraphRAG technique to the Postgres Legal Research Copilot application to boost the quality of LLM responses and the accuracy of information retrieval pipeline |
| **[Microsoft Foundry Community](https://aka.ms/MicrosoftFoundryDiscord-ft27)** | Connect with other learners and experts in our Discord community |

### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the topics in this session.

**GitHub Copilot CLI** — Install with:

```shell
copilot plugin install microsoftdocs/mcp
```

**VS Code** — One-click install:  
[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)

For more information, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

### 👥 Content owners

<table>
<tr>
    <td align="center"><a href="https://github.com/iemejia">
        <img src="https://github.com/iemejia.png" width="100px;" alt="Ismaël Mejía"/><br />
        <sub><b>Ismaël Mejía</b></sub></a><br />
            <a href="https://github.com/iemejia" title="talk">📢</a>
    </td>
</tr></table>

### Deliver this session

Presenters and re-delivery partners can find the deck, recordings, presenter
notes, and delivery guidance in [`delivery-resources/`](delivery-resources/README.md).

### ⚖️ Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.

Any use of third-party trademarks or logos are subject to those third-party's policies.
