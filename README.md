# ASCII Artist Chatbot

This repository contains an ASCII Artist Chatbot powered by the ChatGPT API. The chatbot interacts with users, receives input in the form of messages, and generates ASCII art representations based on the input.

![00162-3657876095](https://github.com/Aravinda89/ASCII_artist_chatbot/assets/31471559/3d8fb11e-fa8c-4d2c-bead-65b9dcb666d6)

## Features

- Interactive chat-based interface
- Utilizes OpenAI's ChatGPT API 
- Generates ASCII art based on user input
- Displays conversation history with user and chatbot responses

## Setup

To run the ASCII Artist Chatbot locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Aravinda89/ASCII_artist_chatbot.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API credentials:

   - Create an account on the OpenAI platform (if you haven't already)
   - Obtain an API key
   - write API key inside `.env` file
   - API_KEY = sk-*********************

4. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

5. Access the chatbot interface in your web browser at `http://localhost:8501`.

## Usage

Once the Streamlit app is running and you've accessed the chatbot interface, follow these steps to interact with the ASCII Artist Chatbot:

1. The chatbot will provide a system message to explain its purpose and instructions.

2. Enter your messages in the input box provided and press Enter.

3. The chatbot will respond with ASCII art based on your input.

4. Continue the conversation by entering additional messages.

5. The chat history will be displayed, showing both user and chatbot responses.

## Example

Here's an example conversation with the ASCII Artist Chatbot:

![ezgif-2-a1f926d6dd](https://github.com/Aravinda89/ASCII_artist_chatbot/assets/31471559/0b943717-6196-4e1c-9430-f3b2ff9d9870)

## Contributing

Contributions to the ASCII Artist Chatbot are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## References

- OpenAI. OpenAI ChatGPT API. Retrieved from [https://openai.com/docs/api/](https://openai.com/docs/api/)
- Streamlit. Streamlit Documentation. Retrieved from [https://docs.streamlit.io/](https://docs.streamlit.io/)
- Awesome ChatGPT Prompts  https://github.com/f/awesome-chatgpt-prompts

