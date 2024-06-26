# Kishan ChatBot

## Overview

Kishan ChatBot is a conversational agent powered by the Meta-Llama-3-8B-Instruct model. This chatbot provides an interactive interface for users to engage in text-based conversations on various topics.

## Features

- **Real-time Interaction:** Users can interact with the chatbot in real-time by typing messages into the input box.
- **Customizable System Prompts:** Users can provide system prompts to guide the conversation.
- **Clear Chat History:** Users can clear the chat history with a single click.
- **Efficient Memory Handling:** Utilizes TextStreamer for efficient memory handling during text generation.

## Demo

Check out the [demo video](https://drive.google.com/file/d/1j-AT1FqSzbxLZxjZ5NPAgMbcQ43qR8PX/view?usp=drive_link) to see Kishan ChatBot in action!


## Usage

1. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

2. Interact with the chatbot by typing messages into the input box.
   
3. Optionally, provide system prompts to guide the conversation.

4. Click the "Clear Chat History" button to clear the chat history.

## Configuration

- The system prompt can be customized by entering text in the corresponding input field.

## Dependencies

- streamlit
- torch
- requests
- transformers

## Acknowledgements

- This project utilizes the Hugging Face Transformers library.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

