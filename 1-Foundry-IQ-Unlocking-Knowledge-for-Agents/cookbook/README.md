# Episode 1 Cookbook: Unlocking Knowledge for your Agents

This folder contains the hands-on cookbook for Episode 1 of The IQ Series.

> **💡 Tip:** You can deploy all required Azure resources automatically with the **Deploy to Azure** button — see the [Episode 1 README](../README.md#-deploy-azure-resources) for details.

## 📓 Cookbook Notebook

The [**Foundry IQ Cookbook**](./foundry-iq-cookbook.ipynb) walks you through Foundry IQ end-to-end, step by step:

1. Creating a knowledge source backed by an Azure AI Search index
2. Creating a knowledge base that pairs your data with an LLM for agentic retrieval
3. Querying the knowledge base and inspecting synthesized answers with citations
4. Connecting Foundry IQ to the Foundry Agent Service so an agent can ground its responses in your data

### Quick Start

1. Install dependencies: `pip install -U azure-search-documents==11.6.0b13 azure-ai-projects azure-identity python-dotenv`
2. Create a `.env` file with your endpoint values (see the notebook for details)
3. Open `foundry-iq-cookbook.ipynb` in VS Code or Jupyter and run the cells

## Additional Resources

- [Episode 1 README](../README.md)
- [Microsoft Foundry Documentation](https://learn.microsoft.com/azure/ai-foundry/)
- [Agentic Retrieval Quickstart](https://learn.microsoft.com/azure/search/search-get-started-agentic-retrieval)
