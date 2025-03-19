# RAG
IPC Section Chatbot
This project is an AI-powered chatbot designed to assist users in retrieving relevant legal sections from the Indian Penal Code (IPC) and related laws. It provides:

 Section Details – Retrieves the IPC section based on the query.
 Defending Sections – Suggests possible defenses for the given section.
 Applicable Laws – Identifies the law under which the section falls.

 How It Works-->
Data Collection: Law PDFs were sourced from Drishti Judiciary.
Text Processing: Applied recursive character splitting for efficient chunking.
Embeddings: Generated using Ollama (Nomic Embed Text) and stored in ChromaDB.
Retrieval & Chatbot Logic: Implemented using LCEL Chain, ensuring accurate responses with well-structured system and human messages.
System Message: Configured to handle the chatbot’s behavior and response structure.
Response Generation: Uses Mistral 7B for generating detailed legal insights.
Features-->
Query any criminal law section, and the bot will provide detailed insights.
Supports legal research by offering defensive legal provisions.
Fast and efficient retrieval of law sections using RAG (Retrieval-Augmented Generation).
 Future Improvements-->
Expand coverage to civil laws and procedural codes.
Improve prompt engineering for more nuanced responses.
Integrate with a legal case database for precedents.
