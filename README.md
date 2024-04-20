# Chat with PDF using Gemini 💁

This project is a Streamlit web application that allows users to ask questions about uploaded PDF documents and receive answers based on the content of those documents. It utilizes the Gemini conversational AI model for answering questions and Google's Generative AI for text embeddings.

## Features

- **Upload PDF Files**: Users can upload one or more PDF files containing text data.
- **Ask Questions**: Users can input questions related to the content of the PDF files.
- **Get Answers**: The application processes the uploaded PDF files, extracts text, and provides answers to user questions based on the extracted content.

## Dependencies

- **Streamlit**: The web application framework used for building the user interface.
- **PyPDF2**: A library for reading PDF files and extracting text.
- **langchain**: A library for text processing and conversational AI.
- **Google Generative AI**: Provides text embeddings and conversational AI capabilities.
- **FAISS**: A library for similarity search, used for efficient text retrieval.
- **dotenv**: For loading environment variables from a .env file.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/amitesh197/PDF_Chatbot/
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Set up Google API Key:

   - Obtain a Google API key with access to the Generative AI service.
   - Create a `.env` file in the project directory.
   - Add your Google API key to the `.env` file:

     ```
     GOOGLE_API_KEY=<your_api_key>
     ```

## Usage

1. Run the Streamlit application:

   ```
   streamlit run app.py
   ```

2. Access the application in your web browser at the provided URL.

3. Upload one or more PDF files containing text data.

4. Ask questions related to the content of the uploaded PDF files.

5. Receive answers based on the extracted content of the PDF files.
