PyPDFBot
A Streamlit application leveraging Google's Generative AI to extract insights from PDF documents.

This project provides a user-friendly interface to upload PDF documents, process them using Google's Generative AI, and obtain answers to questions related to the document content.

Key Features:

PDF Upload: Supports multiple PDF uploads for comprehensive analysis.
Text Extraction: Extracts text from uploaded PDFs for processing.
Vector Store Creation: Creates a searchable vector store using FAISS and Google Generative AI embeddings.
Question Answering: Enables users to ask questions about the document content and receive relevant answers.
Streamlit Interface: Provides a visually appealing and interactive user experience.
Prerequisites:

Python environment with required libraries (specified in requirements.txt)
A Google Cloud Platform project with the Generative AI API enabled
A Google API key with access to the Generative AI service
Installation:

Clone the repository:

Bash

git clone https://github.com/anikethate7/Streamlit_bot

Use code with caution.

Create a virtual environment (recommended):

Bash

python -m venv venv

source venv/bin/activate  # or venv\Scripts\activate on Windows

Use code with caution.

Install dependencies:

Bash

pip install -r requirements.txt

Use code with caution.

Usage:

Set your Google API key in the Streamlit app.
Upload your PDF documents.
Click the "Submit & Process" button to create the vector store.
Ask your questions in the provided text box.
Note:

The api_key should be kept confidential. Consider using environment variables or secure storage for production environments.
The code uses Google's Generative AI services, which may incur costs. Refer to Google Cloud pricing for details.
Contributing:

Contributions are welcome! Please follow standard Git practices for forking, branching, and pull requests.
