# Chat with PDF using Gemini

### Goal 

As someone who frequently learns from PDFs and research papers, I often find the process time-consuming. Skimming through large documents to find specific information can be tedious, and traditional note-taking methods can be cumbersome.

This application is designed to bridge this gap by leveraging the power of Google's Gemini language model

**Key features:**

* Upload multiple PDFs at once for processing.
* Ask questions and retrieve relevant information from the PDF content.
* Get context-aware responses from a powerful language model.

### Example Use
![alt text](https://github.com/Yega-Noragami/Langchain-Gemini-QA/blob/main/Gemini-action.png?raw=true)


### How to Run

**1. Prerequisites**

Before running the application, you'll need to install the required libraries and obtain a Google API key.

**Install libraries:**

```
pip install -r requirements.txt
```

**Obtain Google API Key:**

1. Go to the Google Cloud Console: [https://console.cloud.google.com/](https://console.cloud.google.com/).
2. Enable the Google Generative AI service.
3. Create an API key and set the environment variable named `GOOGLE_API_KEY` to your key value.

**2. Run the application:**

Open your terminal and navigate to the directory containing the application file (e.g., `app.py`). Then, run the following command:

```
streamlit run app.py
```

**3. Using the application:**

1. Upload your PDF files using the file uploader in the Streamlit app.
2. Click the "Submit & Process" button to process the uploaded PDFs.
3. Once processing is complete, ask a question related to the content of the PDFs in the text input field.
4. The application will use the Gemini language model to analyze the PDFs and provide a response to your question.

