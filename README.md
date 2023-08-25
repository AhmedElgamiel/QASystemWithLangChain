# QASystemWithLangChain
A QA system to answer question from 5 different papers

**We develope our QA sytem with 5 steps:**
1. Files loading
2. Splitting Files data into chunks
3. Convert these text chunks into vector embeddings and store them into a vector DB
4. Create a Retrieval to retrieve relevant information to a query from the BD
5. Create answer generator that uses retriever to get relevant info and LLM to generate answers based on info passed as a context.
6. Create an agent to use QA tool to solve questions based on ReAcr Reasoning.
