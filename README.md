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

(Given the extensive scope and the focus on integrating multiple LLMs for financial data processing, I’ve realized that completing the entire system within the 36-hour time frame would be challenging. Therefore, I’ve taken the approach of focusing specifically on fine-tuning LLaMA/Mixtral models for financial data analysis to achieve substantial progress.

Steps I've taken so far:
Data Fetching and Preprocessing:
I have fetched public datasets relevant to financial data (e.g., stock prices, market news, regulatory filings) and am currently preprocessing these datasets for model training.

Fine-Tuning Script Setup:
The fine-tuning script has been successfully set up using Hugging Face and QLoRA, designed to efficiently fine-tune LLaMA and Mixtral models for the specific needs of financial data.

Model Training:
I have initiated the fine-tuning process using Colab/Kaggle, focusing on optimizing CPU performance for better model efficiency.

Export & Deployment Plan:
Once the fine-tuning is completed, I plan to export the fine-tuned model and deploy it through Streamlit UI, which will allow for real-time inference and interaction with the data.

Next Steps:
Model Evaluation: Post-training, I will test the model's performance on tasks like sentiment analysis, fraud detection, and financial trend prediction to ensure accuracy.
Deployment: The model will be deployed on a cloud platform for high availability and scalability.
System Integration: Following deployment, I will work on integrating this model into a larger financial AI infrastructure for low-latency execution and risk prediction.)



Challenges Faced-
Authentication Issues Faced for Dataset Downnloading-Tackled By Manually Download Those
Model Deployment-Authenctication issues for accesing Llama model from hugging face

