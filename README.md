# Virtual Voice Assistant with Llama-LLM

The Python Code allows the end-user to communicate with a desktop computer by voice and it also responds to the voice instructions given by the user. The assistant is designed in such a way that it takes the user input in the form of verbal commands, displays the input, processes it, and returns the output in various forms, like action to be performed or the verbal result is dictated to the end-user.

![image](https://github.com/phoenix-mp3/VVA-LLM/assets/128579996/a2f02862-8afe-4fa1-b4ce-2ad11ee16cf0)

Text to speech is a way of transforming a response to convey what was done if an action was taken or to show that it did not understand. Text to speech (TTS) has a variety of options. There are several non-AI alternatives available, like speech_recognition, gTTS, and much more.

Voice Assistant helps with accessing and browsing webpages like Gmail, YouTube, The Times of India, and Google. It also plays a song at the user's instruction. The voice bot can access the system camera and take pictures and videos upon the user's instructions. Handling system brightness and volume on user's hand gestures, which are recognized using the camera, are some highlights of the Assistant.

On the whole, the virtual voice assistant is a bot that helps the user handle all tasks on the system using verbal directives and reduces manual actions. This code allows the end-user to communicate with a desktop computer by voice, and it also responds to the voice instructions given by the user. The assistant is designed in such a way that it takes the user input in the form of verbal commands, displays the input, processes it, and returns the output in various forms, like action to be performed or the verbal result is dictated to the end-user.

This can be directly implemented on personal computers and can be analyzed and tested in real-time.

## New Integration with Streamlit and LangChain

The new code integrates Streamlit for a web interface and LangChain for enhanced conversational AI capabilities. 

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/phoenix-mp3/virtual-voice-assistant-naruto.git
   cd virtual-voice-assistant-naruto
   ```

2. **Create and activate a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   Create a `.env` file in the project root directory and add the following variables:
   ```env
   LANGCHAIN_TRACING_V2=true
   LANGCHAIN_PROJECT=App-LLM
   LANGCHAIN_API_KEY=your_langchain_api_key
   ```

## Usage

1. **Run the Streamlit application**:
   ```bash
   streamlit run llama_app.py
   ```

2. **Interact with the application**:
   - Open your web browser and go to `http://localhost:8501`.
   - Enter your question in the input box and press Enter.
   - The response from the Llama model will be displayed on the page.

## Environment Variables

The application relies on the following environment variables, which should be defined in a `.env` file:

- `LANGCHAIN_TRACING_V2`: Enable tracing for Langchain (set to `true`).
- `LANGCHAIN_PROJECT`: The project name for Langchain.
- `LANGCHAIN_API_KEY`: Your Langchain API key.

## Project Structure

```
virtual-voice-assistant-naruto/
│
├── llama_app.py            # Main application code
├── requirements.txt        # Project dependencies
├── .env.example            # Example environment variables file
├── README.md               # Project documentation
└── other_files             # Other necessary files for the project
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Langchain](https://github.com/langchain-ai/langchain)
- [Streamlit](https://streamlit.io/)
- [Ollama](https://ollama.com/)
- [Groq](https://groq.com/)

```

### Example `requirements.txt`:
```txt
langchain-openai
langchain-core
langchain-community
langchain-groq
python-dotenv
streamlit
```

### Example `.env` file:
```env
LANGCHAIN_TRACING_V2=true
LANGCHAIN_PROJECT=App-LLM
LANGCHAIN_API_KEY=your_langchain_api_key
GROQ_API_KEY=your_groq_api_key
```
