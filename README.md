# AI-Powered-Chatbot-with-AWS-Bedrock-RAG

## 🚀 Overview
This project demonstrates how to build a personalized AI chatbot that can answer questions based on custom documents. By leveraging **Amazon Bedrock, OpenSearch Serverless, and Amazon S3**, this chatbot efficiently retrieves and processes data using **RAG (Retrieval-Augmented Generation)** to generate accurate, context-aware responses.
![image](https://github.com/user-attachments/assets/86799a7c-5a14-4876-9dcb-42a02a7e3152)

## 🏗️ Services Used
- **Amazon Bedrock** – AI model management and inference
- **Amazon OpenSearch Serverless** – Vector database for efficient retrieval
- **Amazon S3** – Storage for personal documents

## 📌 Key Features
✅  **Retrieval-Augmented Generation (RAG):** AI chatbot trained on custom documents**    
✅  **Amazon Bedrock Integration:** Uses **Titan Text Embeddings v2 & Llama 3** for response generation**    
✅  **Amazon OpenSearch Serverless:** Fast and scalable vector-based search**    
✅  **Amazon S3 Storage:** Secure document storage and retrieval**    
✅  **Knowledge Base (KBase) Setup:** Stores and organizes chatbot data efficiently**    
✅  **Customizable Chatbot Responses:** Fine-tune responses by adjusting source chunks and prompts**    

## 🏗 Project Architecture  
1️⃣  **Store documents in Amazon S3**  
2️⃣  **Create a Knowledge Base in Amazon Bedrock**  
3️⃣  **Use OpenSearch Serverless for vector search**   
4️⃣  **Sync data from S3 to Knowledge Base**  
5️⃣  **Integrate AI models for response generation**  
6️⃣  **Deploy and test the chatbot**    


## 🔧 Tech Stack  
- **AWS Bedrock** – AI Model Hosting & Knowledge Base  
- **Amazon OpenSearch Serverless** – Vector Search & Querying  
- **Amazon S3** – Document Storage  
- **Titan Text Embeddings v2 & Llama 3** – AI Model for NLP  
- **Python & AWS SDK** – Integration & API Calls  

## 💡 How It Works  
1️⃣ **User asks a question** → AI model interprets it  
2️⃣ **Knowledge Base retrieves relevant document data**  
3️⃣ **AI model processes & generates a response**  
4️⃣ **Chatbot responds with an AI-generated answer**  

## 🚀 Getting Started  
### 🔹 Step 1: Setting Up a Knowledge Base
- Navigate to **Amazon Bedrock → Knowledge Bases**
- Create a **Knowledge Base with Vector Store**
- Store personal documents in **Amazon S3** for retrieval
- Use **IAM roles** to grant Bedrock access to S3

### 🔹 Step 2: Storing Documents in Amazon S3
- Create an **S3 bucket** in the same AWS region (e.g., `us-east-2`)
- Upload **personal or company documents** for chatbot training

### 🔹 Step 3: Connecting Knowledge Base to Data Source
- Link the **S3 bucket** to the **Knowledge Base** in Bedrock
- Configure **parsing strategy** (text extraction) & **chunking** for efficient search
- Select **Titan Text Embeddings v2** for vector representation

### 🔹 Step 4: Enabling AI Models in Amazon Bedrock
- Navigate to **Bedrock Model Access**
- Enable **Titan Text Embeddings v2, Llama 3.1 8B Instruct, Llama 3.3 70B Instruct**
- Accept terms & submit for approval

### 🔹 Step 5: Synchronizing Knowledge Base
- Sync S3 data with the **Knowledge Base**
- Configure **OpenSearch Serverless** for **vector retrieval**

### 🔹 Step 6: Testing and Refining the Chatbot
- Select **Llama 3.1 8B Instruct** model for inference
- Ask sample queries to test response quality
- Switch to **Llama 3.3 70B Instruct** for improved performance if needed

---

## 🎯 Optimizing Chatbot Responses
- Increase **number of source chunks** for broader context
- Customize **prompts** for refined chatbot behavior
- Compare **response quality** using different models

### 💡 Example Query:
❓ *"What AWS services were used to build this chatbot?"*  
✅ The chatbot retrieves data from the **Knowledge Base** and provides a well-structured answer.

---
## 🔥 Use Cases  
🔹 **Customer Support Chatbots** – Automate responses using documentation  
🔹 **Research Assistants** – Retrieve legal, medical, or technical knowledge  
🔹 **AI-Powered Personal Assistant** – Train chatbot on personal/company data  


