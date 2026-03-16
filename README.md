# Thesis_Chatbot
Chatbot Development for Database Information Search and Management

Thesis Description
This thesis aims to implement an intelligent conversational system for searching and managing information from a database.
The system allows the user to submit queries in natural language and receives answers directly based on the data available to the system. To achieve this goal, a hybrid architecture is used that combines two techniques. RAG (Retrieval-Augmented Generation) technique for searching documents and texts, and Text-to-SQL for executing queries in structured relational databases.
It analyzes each question and with a routing mechanism (Intent Router), it automatically decides which technique is appropriate to provide the correct answer. In addition, the system supports data processing functions, allowing the user to insert, modify and delete documents through natural language.

For the implementation
• Python and FastAPI will be used for the backend
• LangChain will be used for the management of language chains
• ChromaDB for the vector database
• OpenAI's GPT-4o-mini as the central language model as it has low cost and very good accuracy for RAG and Text-to-SQL
• The frontend will contain a chat interface with streaming response capabilities
