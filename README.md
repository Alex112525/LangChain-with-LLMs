# LangChain with LLM's
This repository contains a collection of notebooks showcasing the combination of various Huggingface models with the Langchain framework. The notebooks serve as experiments to explore the responses and behaviors of different language models.

## Notebooks

### 1. LangChain_promps_and_Chains: 
* This notebook uses HuggingFace's BERTin-GPT-j-6B-Alpaca language model to generate enhanced responses based on an initial text string. The main goal of the notebook is to improve the responses generated by the BERTin-GPT-j-6B-Alpaca model by using techniques such as Prompt Templates and Sequential Chains.

### 2. LangChain_FewShotPromptTemplate:
* In this notebook, we employ the BERTin-GPT-j-6B-Alpaca language model using "Few Shot Prompting" with the Langchain framework. The goal is to enhance the model's responses by providing it with prompt examples and fine-tuning it on a specific task.

### 3. LangChain_BufferMemory:
* This notebook showcases the usage of the BERTin-GPT-j-6B-Alpaca language model with the ConversationBufferMemory from the Langchain framework. By incorporating conversation memory, the model can provide more contextually aware responses based on the ongoing conversation.

### 4. LangChaing_BufferWindowsMemory:
* This notebook demonstrates the utilization of the Falcon-7B-instruct language model with the ConversationBufferWindowMemory from the Langchain framework. The model is equipped with a conversation buffer window, allowing it to retain a defined context window from the ongoing conversation and generate more informed responses.

### 5. LangChain_SummaryMemory:
* This notebook utilizes the Falcon-7B-instruct language model with the ConversationSummaryMemory from the Langchain framework. The model is intended to be provided with a summarized context of the ongoing conversation, generated by the same model. Unfortunately, the model's performance fell short of expectations, and the responses were not as robust as desired.

### 6. LangChain_Documents:
* This notebook provides an in-depth exploration of the Langchain Document class. The Document class is a fundamental component of the Langchain framework, designed to encapsulate and manage various attributes of text documents. 

### 7. Loaders and Splitting with Langchain:
* In this notebook, Langchain is utilized to load documents from various sources using specialized loaders. The notebook demonstrates the use of the PyPDF library for loading PDF documents and the WebBaseLoader for extracting content from web pages. Additionally, the notebook showcases the functionality of Splitting functions such as RecursiveCharacterTextSplitter and TokenTextSplitter to process and split the loaded documents into manageable parts for further analysis.

### 8. Embeddings and VectorStores with Langchain:
*  In this notebook, Langchain is employed to convert texts from PDFs into vectors using embedding models. The notebook showcases how to use pre-trained embedding models to represent text documents as numerical vectors. Furthermore, it demonstrates how to perform similarity searches based on cosine similarity to find documents with similar content. Additionally, the notebook explores the integration of Chroma, a database system, to store and efficiently retrieve embeddings for faster similarity searches.

>Note: This repository will be updated with additional notebooks over time, each focusing on different aspects of combining Huggingface models with the Langchain framework. Stay tuned for more experiments and insights!

Feel free to explore the notebooks and experiment with different models and setups. If you have any questions or suggestions, please don't hesitate to reach out.
