# Chat with Gemini

This repository contains a simple chat application named "Chat with Gemini," powered by Google's Generative AI. Users can interact with the AI model by typing prompts, and the AI will respond accordingly.

## Features

- **Interactive Chat Interface**: Engage in real-time conversations with the Gemini AI model.
- **User-Friendly Design**: Simple and intuitive interface for seamless interaction.
- **AI-Powered Responses**: Receive intelligent and context-aware replies from the AI.

## Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/udit710/chat-with-gemini.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd chat-with-gemini
   ```

3. **Install Dependencies**:

   Ensure you have [Python 3.x](https://www.python.org/downloads/) installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**:

   Create a `.env` file in the project root directory and add your Google API key:

   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

   Replace `your_api_key_here` with your actual API key.

5. **Run the Application**:

   ```bash
   python app.py
   ```

   The application will start, and you can access it via your web browser at `http://localhost:5000`.

## Usage

- **Start a Conversation**: Type your message into the input field and press Enter to send.
- **Receive Responses**: The AI will process your input and provide a relevant response.
- **Continue the Dialogue**: Engage in an ongoing conversation by sending additional messages.

## Acknowledgments

- [Google's Generative AI](https://ai.google/) for powering the chatbot.
- [Streamlit](https://streamlit.io/) for providing an easy-to-use framework for building the web interface.

*Note: Ensure you comply with Google's API usage policies and guidelines when using this application.* 
