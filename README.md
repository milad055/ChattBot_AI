
# Chatbot AI


# Overview
This Python-based Chatbot AI is designed to engage in conversations with users, providing responses based on predefined messages. The chatbot uses a simple algorithm to determine the most suitable response for a given user input.




## Features

- Message Probability Calculation: The chatbot calculates the probability of a user message matching predefined responses.
- Customizable Responses: Responses are customizable and can be easily extended to include new messages.
- Long Responses: Supports longer responses for more detailed interactions.

# Getting Started
Prerequisites:

Python installed on your machine.

Required libraries: re




## Installation

1. Clone the repository to your local machine.

```bash
  git clone https://github.com/your-username/your-repo.gitcd your-repo
```
1. Install the required dependencies.
```bash
  pip install -r requirements.txt
```



    
## Usage

1. Open the chatbot.py file in your preferred Python IDE (e.g., PyCharm).

2. Run the script.

3. Interact with the chatbot by entering messages when prompted.







## Customization
Adding New Responses

To add new responses, modify the check_all_messages function in chatbot.py. You can define recognized words and specify required words for a response.

```bash
response('Your New Response', ['word1', 'word2'], required_words=['required_word'])
```

Extending Long Responses

Long responses are stored in the long_responses.py file. You can extend or modify the responses in this file to enhance the chatbot's capabilities.
## Examples
```bash
# Simple response
response('Hello!', ['hello', 'hi', 'hey', 'sup', 'heyo'], single_response=True)

# Longer response
response(long.R_ADVICE, ['give', 'advice'], required_words=['advice'])

```


## Contributing

Contributions are always welcome! If you have ideas for improvement or new features, feel free to open an issue or submit a pull request.


## License



## Feel free to update the sections and details based on your project structure and preferences.


