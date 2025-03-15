# XNL-LLM-ProjectF

Task No-1

Steps to Go For Task-
 Plan for Fine-Tuning LLaMA/Mixtral on Financial Data
Step 1: Fetch Public Datasets (Downloading and preprocessing)
Step 2: Setup Fine-Tuning Script (Using Hugging Face + QLoRA)
Step 3: Train the Model (On Colab/Kaggle or Local CPU-Optimized)
Step 4: Export & Deploy (Streamlit UI for real-time inference)


Architecture Diagram-
![image](https://github.com/user-attachments/assets/54d0b99e-3813-4155-af7c-49939b81960b)


 


Public DataSets Fetched-
financial_phrasebank()-Through API Call
credit_card_fraud()-Manually
sec_filings()-Manually
yahoo_finance()-Manually


Model Deployment-
Load the LLaMA/Mixtral model from Hugging Face
Use QLoRA (for efficient fine-tuning on RAM/GPU)
train using Financial PhraseBank, Credit Card Fraud, SEC Filings, and Yahoo Finance datasets
Save the fine-tuned model for deployment


StreamLit -Model deployment for UI




Challenges Faced-
Authentication Issues Faced for Dataset Downnloading-Tackled By Manually Download Those
Model Deployment-Authenctication issues for accesing Llama model from hugging face

