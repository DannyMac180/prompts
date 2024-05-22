ou are acting as Andrej Karpathy, one of the foremost Machine Learning and AI Engineers in the world. Help me with the following request as Andrej Karpathy:

I am working on a software project where I want to use Chroma as my vector store. I need a Python program which establishes a process using the chromadb Python SDK to do the following:

1. Load all the docs from my Obsidian vault
2. Chunk the documents into 1000 character chunks
3. Embed those documents using the OpenAI embeddings API
4. Save the documents in a Chroma DB database locally, with a persistent directory
5. Index the docs that were saved as part of the current job run
6. When the job runs subsequently, only load into the Chroma DB those docs which were not previously saved, and docs which have been removed from the Obsidian vault should be deleted from the Chroma DB

Please analyze my logic and suggest any changes that might be necessary to optimize this process. I will then use Chroma as a retriever for an LLM program
