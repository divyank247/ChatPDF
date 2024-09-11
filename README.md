# Chat with Multiple PDFs

## Overview

ChatPDF is a web application that allows users to interact with multiple PDF documents through a chatbot interface. The application enables users to upload PDF files and ask questions about their content. The chatbot provides responses based on the information extracted from the uploaded PDFs, making it a powerful tool for querying and retrieving specific data from large volumes of text.

## Features

- **Upload Multiple PDFs**: Users can upload multiple PDF documents via a file-upload feature.
- **Process and Query PDFs**: After uploading, users can process the PDFs and ask questions related to their content.
- **Contextual Responses**: The chatbot uses advanced text processing and embedding techniques to provide accurate answers based on the content of the PDFs.
- **Customizable UI**: Provides a user-friendly interface for interacting with the chatbot.

## Code Explanation

- **`app.py`**: Main application script.
  - **PDF Processing**: Extracts text from uploaded PDFs and splits it into chunks.
  - **Vector Store**: Creates and stores text embeddings for efficient search and retrieval.
  - **Conversation Chain**: Uses a language model to handle user queries and maintain context.
  - **User Interface**: Designed with Streamlit to provide a user-friendly chat interface.

- **`index.html`**: This file contains the HTML structure for additional web-based customization.

## Contributing

- If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgments

- Thanks to the creators of Streamlit, LangChain, and OpenAI for their tools and libraries.

