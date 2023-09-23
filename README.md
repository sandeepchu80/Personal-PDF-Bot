# Personal-PDF-Bot
This documentaion helps the user to create a GUI in oder to upload their personal PDF files for asking questions related to that PDF files or to summarize it. Thus leverages the work of the user!

Utilizing GPT-3.5 (ChatGPT) for personal PDF files with the help of langchain, this Python application enables the user to import a PDF document and inquire about its content using natural language. The application leverages a Large Language Model (LLM) to generate responses based on the PDF's content.

## Working Mechanism
The program processes a PDF document by segmenting its text into smaller units, which are subsequently converted into vector representations using OpenAI embeddings. Next, it identifies text segments that bear semantic resemblance to the user's inquiry and supplies these segments to a Language Model (LLM) for generating a response.

For the "Proof of Concept" stremlit has been used to create simple GUI.

## Steps to be followed in order to run the website for the "Proof of Concept" using streamlit are:

### Step 1:
open the required folder in visual studio code

### Step 2:
Change the directory using "cd" command where the application file is located, for instance: cd Personal-PDF-Bot

### Step 3:
In order to install necessary dependencies run this command on that current directory: pip install -r requirements.txt

Donot forget to add your OpenAI API key to the .env file.

### Step 3:
Now the application is ready to use. Run this command in the terminal: streamlit run app.py

After the application opens in separate website you can upload your PDF file and inquire it. Remember not to upload PDF file larger than 200MB otherwise it will hit the limit.

![](GUI%50image.png)

