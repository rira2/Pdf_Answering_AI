# Project overview:
This is a pdf answering ai , which answers all your questions related to the pdf of your concern.The user needs to upload the pdf the to webpage and then the model will start proceesing so that the user can ask any questions related to the pdf they uploaded. 

# Installation instructions:
### (to run the project using vscode)
1. Clone the git repo using git clone in vscode.
2. Create a virtual environment,now install all the required libraries as listed in requirements.txt to set up the environment for the project to run.
3. Make sure that folders named 'document' and 'db' exist in the same folder of the project where all codes are already existing.If not then do so.
4. Make sure that you install downgrade version of chromadb using (pip install --upgrade chromadb==0.3.29) as on new version,migration of data works differently.
5. Download 'LaMini-T5-738M' file from internet using git clone and save the file in the same project folder.
6. To run the project follow 'usage' steps.

# Usage
1. Run the 'ingestion.py' and 'constant.py' file.
2. Now,start the application using 'streamlit run Pdf_Answering_AI.py'
3. Now thw appliaction will open ,then simply upload the file and ask your questions.
# Dependencies
 ### The basic libraries required for the project are(listed in requirements.txt):
langchain
streamlit
transformers
torch
einops
bitsandbytes
accelerate
pdfminer.six
bs4
sentence_transformers
duckdb
chromadb==0.3.29
beautifulsoup4
sentencepiece
six
requests
uvicorn
torchvision
streamlit-chat
numpy 
langchain_community
 #### and the basic dependency is a good system to run , a 16 GB RAM system will do better, but it runs very well in 8GB RAM as well.
