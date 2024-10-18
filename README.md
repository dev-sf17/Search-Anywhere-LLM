# Search-Anywhere-LLM

Here's a README description for your LLM chatbot based on the details provided:

---

# Search-Anywhere Chatbot

**Search-Anywhere** is a powerful chatbot designed to provide information from multiple sources, including Wikipedia, Arxiv, and a general web corpus. Developed using the LangChain framework, this chatbot ensures accurate and context-aware responses, enhancing the user's search experience.

## Features

- **Multi-Source Information Retrieval**: The chatbot can access and retrieve information from Wikipedia, Arxiv, and a web corpus, making it a versatile tool for various topics and fields.
- **LLM Integration**: The chatbot is powered by the **Llama3-8b-8192** model via the Groq API, providing high-quality, context-aware responses to user queries.
- **RAG Implementation**: Retrieval-Augmented Generation (RAG) is employed to enhance the chatbot's ability to deliver relevant and precise information by utilizing context from chat history and user queries.
- **CallBackHandler**: A CallBackHandler is integrated to track the chat history and maintain the flow of the conversation, ensuring that the chatbot responds accurately according to the given context.
- **Streamlit Cloud Deployment**: The chatbot is deployed on **Streamlit Cloud**, making it accessible to users directly from a web interface.

## Technical Details

- **Framework**: LangChain
- **LLM Model**: Llama3-8b-8192 (via Groq API)
- **RAG & CallBackHandler**: Used for context management and improving chatbot interaction
- **Deployment**: Streamlit Cloud for easy accessibility

## Usage

To use the chatbot, visit https://search-anywhere-llm-e6a57kgkhdbhnrje44adbn.streamlit.app/

## Installation

If you want to run the chatbot locally or deploy it elsewhere, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Search-Anywhere-LLM.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Search-Anywhere
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```
_______________________________________________________________________________________________________________________________________________
This version specifies that the project is based on a practical demonstration in a Udemy course for skill development and practice.
