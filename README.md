# SmartSDLC

SmartSDLC - AI-Enhanced Software Development Lifecycle

SmartSDLC is a powerful AI assistant that streamlines software development tasks by leveraging IBM Watsonx's Granite LLM models. This Streamlit web application offers a suite of intelligent SDLC modules to assist developers and product teams at every phase.

🚀 Features

This AI-powered assistant includes the following modules:

📥 Requirement Upload & Classification

   Upload PDF requirement documents.
   Automatically extract and classify content into SDLC phases.
   Generates structured user stories from raw requirements.

💻 AI Code Generator

   Converts natural language prompts into working Python code.

Bug Fixer

   Automatically detects and corrects issues in your code snippets.

🧪 Test Case Generator

   Generates unit test cases using unittest or pytest based on your code or requirements.

Code Summarizer

   Produces concise summaries and explanations for given code snippets.

💬 Chat Assistant

   Interactive chatbot for any SDLC-related queries or coding help.

🧰 Tech Stack

Frontend: Streamlit

AI Backend: IBM Watsonx.ai with Granite LLMs

PDF Parsing: PyMuPDF (fitz)

Language: Python 3.12+

🔐 IBM Watsonx Setup

To run this app, you need to configure IBM Watsonx credentials:

api_key = "<YOUR_API_KEY>"

project_id = "<YOUR_PROJECT_ID>"

base_url = "https://.ml.cloud.ibm.com"

model_id = "ibm/granite-3-3-8b-instruct"
