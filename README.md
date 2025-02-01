# Financial AI Assistant - RAG Model

## Project Overview
This project implements a Retrieval-Augmented Generation (RAG) model that enables users to analyze Profit & Loss (P&L) statements. Users can upload a financial PDF, ask questions, and receive relevant insights from the document. The solution uses LangChain and Streamlit to provide an interactive web-based interface for querying financial data.

## Features
- **Upload Financial PDF:** Upload a Profit & Loss (P&L) statement in PDF format for analysis.
- **Query Financial Data:** Ask specific financial questions, and the assistant retrieves and processes the relevant information.
- **Structured Responses:** The assistant generates answers in the form of bullet points, tables, or calculations based on the provided data.

## Technologies Used
- **Python** (Primary Programming Language)
- **Streamlit** (For Web Interface)
- **LangChain** (For Query Handling and Retrieval)
- **Pinecone** (Vector Database for Embeddings)
- **Google Generative AI (Gemini)** (For NLP and Embeddings)
- **PyPDFLoader** (For PDF Processing)
- **Ngrok** (For Deployment)

## Setup Instructions

### Requirements
- Python 3.7+
- Install the necessary dependencies:
  ```bash
  pip install -r requirements.txt


###Environment Variables
- Set the PINECONE_API_KEY for Pinecone.
- Set the GOOGLE_API_KEY for Google Generative AI.


###Running the Application
- 1.Start the application locally
- streamlit run app.py


- 2.To deploy it externally, you can use ngrok
- ngrok http 5000


###Usage
- Upload a financial PDF (P&L statement).
- nter a financial query.
- The system will process the query and return relevant insights.


###Contributing
- Feel free to fork this repository, make improvements, and submit pull requests. Please ensure all code follows the existing conventions and passes relevant tests.


