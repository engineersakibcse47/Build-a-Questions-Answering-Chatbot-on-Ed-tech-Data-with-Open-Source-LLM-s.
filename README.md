# Build a Questions-Answering Chatbot on Ed-tech Data with Google Palm Open Source LLMs.

# Project Highlights

- Use a real CSV file of FAQs that Codebasics company is using right now. 
- Their human staff will use this file to assist their course learners.
- We will build an LLM based question and answer system that can reduce the workload of their human staff.
- Students should be able to use this system to ask questions directly and get answers within seconds

### Project Structure

main.py: The main Streamlit application script.
langchain_helper.py: This has all the langchain code
requirements.txt: A list of required Python packages for the project.
.env: Configuration file for storing Google API key.

## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py
```

2.The web app will open in your browser.

- To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

- Once knowledge base is created you will see a directory called faiss_index in your current folder

- Now you are ready to ask questions. Type your question in Question box and hit Enter

## Sample Questions
  - Do you guys provide internship and also do you offer EMI payments?
  - Do you have javascript course?
  - Should I learn power bi or tableau?
  - I've a MAC computer. Can I use powerbi on it?
  - I don't see power pivot. how can I enable it?
