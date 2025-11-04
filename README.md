Med Prep Bot
A MedMCQA-powered Question Answering Bot for Rapid Medical Exam Preparation

Project Overview
Med Prep Bot enables interactive medical exam practice using the MedMCQA dataset. Just type a clinical or theory question this Colab-powered bot retrieves the most relevant Q&A from the MedMCQA set and provides accurate answers, explanations and references instantly. Built with advanced Retrieval-Augmented Generation (RAG), FAISS vector search and transformer models for high-quality, referenced, context-aware responses.

Features
1. Instant QA: Ask any medical question and get a direct, referenced answer.
2. Real Exam Data: Uses the MedMCQA open dataset of medical exam questions, answers and explanations.
3. Intelligent Retrieval: Utilizes FAISS vector search and Sentence-Transformers for semantic similarity.
4. Auto-Explanation: Provides not just the answer, but the full clinical explanation.
5. Extensible Code: Run as a Python Colab notebook for further experimentation.

Tech Stack
1. Python 3 (Colab)
2. Sentence-Transformers (HuggingFace)
3. Transformers (QA model)
4. FAISS (vector database for retrieval)
5. LangGraph/LangChain
6. google/flan-t5-large
7. cross Encoder
8. pandas
9. numpy
10. torch
11. Auto Tokenizer

How It Works
1. User Input: Ask a medical question in the notebook UI.
2. Vector Embedding: The question is embedded using a sentence-transformer model.
3. FAISS Search: The embedding is matched to the nearest entries in the MedMCQA question database.
4. Answer & Explanation Retrieval: The most relevant answer and its explanation are retrieved and formatted for the user.
5. Display: Answer, explanation and reference are shown in the output.

Data Setup & Usage
Download Required Data: To run this notebook, you need three MedMCQA data files.
Please follow these steps:
1. Download the required files from this shared Google Drive folder: (https://drive.google.com/drive/folders/1HsvYmXaurYWeccXm0EDMyA6htv88VlZs?usp=sharing)
2. Colab notebook: Open med-prep-bot.ipynb in Google Colab & upload downloaded files throuh Colab files tab.
2. Run the cell to load the MedMCQA dataset and FAISS index.
3. Enter your medical question when bot is prompted through the HuggingFace (https://huggingface.co/datasets/openlifescienceai/medmcqa/viewer/default/train?views%5B%5D=train&row=51).
4. View the answer and explanation.

License
Note: The MedMCQA dataset is licensed see the dataset’s own license on HuggingFace. So, Use the downloaded data set only for exam prep to run the colab med-prep-bot. 
Do not use this downloaded data and python code for illegal activity or misuse.


  
