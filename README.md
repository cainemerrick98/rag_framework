# RAG Framework
A framework for building retrieval augmented generation applications. The back end will be a Django rest framework api with a react front end

All retrieval augmented generation applications will follow a very similar structure, so why not create a framework that can be quickly configured to set one up? All we will need is a vector database to store the embeddings of documents, a get request api endpoint to receive and transform queries and some api end point that can talk to a LLM. 
