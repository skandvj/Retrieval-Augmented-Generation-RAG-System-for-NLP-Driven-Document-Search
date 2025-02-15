# Vector Store Query Analysis

This repository contains a Jupyter Notebook that explores Vector Store Query Design, leveraging various AI/ML tools such as LangChain, LlamaIndex, FAISS, Pinecone, OpenAI, and HuggingFace.

## Project Overview
The notebook performs an in-depth analysis of vector databases and query designs for information retrieval. The tasks covered include:
- Experimenting with vector store query designs.
- Using different embedding models for text vectorization.
- Storing and retrieving vector representations using FAISS and Pinecone.
- Comparing performance between various retrieval methods.

## Setup and Installation

### Prerequisites
Ensure you have Python 3.8+ installed on your system. Install dependencies using:

```sh
pip install -r requirements.txt
```

Alternatively, manually install necessary packages:

```sh
pip install ipykernel langchain_experimental llama-index-vector-stores-pinecone ipykernel PyMuPDF pinecone-client pypdf faiss-cpu langchain_community transformers sentence_transformers
```

### Running the Notebook
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/vector-store-analysis.git
   cd vector-store-analysis
   ```
2. Install dependencies (as mentioned above).
3. Launch Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open `hw2-rag.ipynb` and execute the cells in order.

## Key Libraries Used
- **LangChain**: Framework for building AI-powered applications.
- **LlamaIndex**: Indexing and retrieval for LLMs.
- **FAISS**: Vector search library by Facebook AI.
- **Pinecone**: Cloud-based vector database.
- **HuggingFace Transformers**: Pre-trained transformer models.
- **OpenAI API**: GPT-powered embeddings and models.

## Results and Insights
The notebook compares various retrieval strategies and their effectiveness. It showcases how different vector store implementations impact search relevance and performance.

## Contributing
Feel free to fork this repository, create a feature branch, and submit pull requests.

## License
This project is licensed under the MIT License.

## Author
Skand Vijay
