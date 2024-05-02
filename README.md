# Conversational-AI-Tutor
"Conversation AI Tutor" is an interactive learning tool that uses AI to provide personalized, conversational tutoring in various subjects, enhancing user understanding.

This project implements a user-friendly AI chatbot interface using Streamlit and Google GenerativeAI. Users can interact with the chatbot by typing messages in the chat window, and the model will generate responses based on the conversation history.

**Features**

- Streamlit-based interactive interface
- Integration with Google GenerativeAI's Gemini 1.5 Pro model
- Utilizes session state to manage conversation history
- Error handling for API access issues

**Requirements**

- Python 3.x
- Streamlit
- Google GenerativeAI API access (refer to Google's documentation for setup)
- `GEMINI_KEY` environment variable (set the API key obtained from Google)

**Installation**

1. Clone this repository.
2. Install the required dependencies:

   ```bash
   pip install streamlit google-generativeai
   ```
   
3. Set your Google GenerativeAI API key:
   
- Create a project and enable the Google GenerativeAI API in your Google Cloud Platform console (https://cloud.google.com/ai/generative-ai).
- Obtain your API key and set the GEMINI_KEY environment variable:
```
export GEMINI_KEY=your_api_key
```
- Alternatively, you can add the API key directly to the code in the ######## section (not recommended for security reasons).

**Running the Application**
   1. Start the Streamlit app in the terminal/command prompt:
      
      ```bash
      streamlit run chat_bot.py
      ```
   2. Access the app in your web browser at http://localhost:8501.

**Usage**
   - Type your messages in the chat input box and press Enter to interact with the chatbot. The chatbot's responses will be displayed below.
   - The chat history is preserved for reference.

**Contributing**
   - We welcome contributions to this project! Feel free to open pull requests with your improvements.

**License**
   - This project is licensed under the MIT License (https://opensource.org/license/mit).
