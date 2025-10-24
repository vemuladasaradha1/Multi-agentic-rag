. Let’s create our multi-agent RAG system
In this section, we will create each of the agents present in our RAG system.

We will have 3 agents managed by a central one (refer to the image for details):

🕵💬 Web search agent: It will include the DuckDuckGoSearchTool tool and the VisitWebpageTool. As you can see, each agent may contain a list of tools.
🕵💬 Retriever agent: It will include two tools for retrieving information from two different knowledge bases.
🕵💬 Image generation agent: It will include a prompt generator tool in addition to the image generation tool.

url : https://huggingface.co/learn/cookbook/multiagent_rag_system
