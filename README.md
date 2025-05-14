# Scrum-Smart-Assistant-AI
# 🛠️ MCP Server Details
The Atlassian Remote MCP Server acts as a secure and standardized backend bridge between your AI assistant and Atlassian’s suite of tools, including Jira and Confluence. It implements the Model Context Protocol (MCP) — a JSON-RPC interface specification that allows AI systems to interact with software tools in a permission-respecting, auditable way.

## 🌐 What is the MCP Server?
The Remote MCP Server, developed and hosted by Atlassian (or optionally self-hosted by you), exposes Jira and Confluence functionality over a single JSON-RPC endpoint. It leverages your existing permissions model to ensure secure, authenticated access to data and actions within your Atlassian cloud.

## ✅ Key Capabilities
The MCP Server enables your smart assistant to:

- Create and update Jira issues

- Add or retrieve Jira comments

- Summarize sprint and board activity

- Search and summarize Confluence content

- Comment on Confluence pages

All these operations are exposed via a uniform JSON-RPC interface, allowing LangGraph to orchestrate tool usage seamlessly.


🔧 You can either use Atlassian’s beta hosted MCP server or run your own instance. For details, refer to Atlassian’s official MCP documentation or request beta access via developer.atlassian.com.



