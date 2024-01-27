# AI chatbot App

A Python AI chatbot with personality that runs in the terminal using the OpenAI GPT-3.5-turbo model

## Prerequisites

Before running this application, ensure that you have the following dependencies installed:

- Python 3.7 or above
- Pip

## Getting Started

Follow the steps below to get started with the Color Palette App:

1. Clone the repository to your local machine.

   ```
   git clone https://github.com/your_username/color-palette-app.git
   ```

2. Install the required dependencies by running the following command inside the project directory:

   ```
   pip install -r requirements.txt
   ```

3. Create a .env file and add an `OPENAI_API_KEY=` field with your open ai key value supplied to it.

## Running the App

After setting up the API key, start the python server by running the following command:

```
python chatbot.py
```

To add a default personality to the chat, add the --personality <personality> to the command:

```
python chatbot.py --personality happy
```

This will start the server in your terminal

## Usage

- Type anything you want to have a conversation with the chatbot
- Press `Enter` to submit the prompt.

The OpenAI GPT-3.5-turbo model will respond based on your input prompt, depending on the personality that you set, it may respond in a different behavior


## License

The AI Chatbot is released under the [MIT License](LICENSE). Feel free to modify and use the code as per your requirements.