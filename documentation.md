# Chatbot Program for Comparing Items
This program is a chatbot that uses OpenAI's GPT-3 API to generate text responses to user's inputs. The program is designed to compare two items that the user wants to buy or know about. The chatbot generates a response based on the comparison between the two items provided by the user.

## Installation
To use this program, you will need an OpenAI API key to authenticate with the GPT-3 API. You can obtain an API key from OpenAI's website. Once you have an API key, you can install the OpenAI Python package using the following command:

`pip install openai`

## Usage
To use this program, run the `chatbot.ipynb` script in a Python environment with the OpenAI package installed. The program will prompt you to enter `1` to start the chatbot, and then you can provide two items that you want to compare.

The chatbot will generate a response based on the comparison between the two items using OpenAI's GPT-3 API. The response will be printed to the console. You can then choose to explore more comparisons or exit the program.

To explore more comparisons, enter `1` when prompted. The chatbot will generate another response based on the same two items, and the response will be printed to the console. You can then choose to explore more comparisons or exit the program.

To exit the program, enter `0` when prompted to play another comparison.

## Documentation
The `chatbot.ipynb` script contains a `chatbot` function that takes a prompt string as an argument and sends it to OpenAI's GPT-3 API to generate a text response. The chatbot function returns the response as a string with leading/trailing whitespaces removed.

The main program contains a loop that prompts the user to enter two items to compare. The program generates a prompt for the `chatbot` function based on the user's inputs and then calls the `chatbot` function to generate a response. The response is printed to the console.

The main program then prompts the user to enter `1` to explore more comparisons or `0` to exit the program. If the user enters `1`, the program generates another prompt for the chatbot function based on the same two items and calls the chatbot function again. The response is printed to the console, and the loop repeats. If the user enters `0`, the program exits the loop and prints a message indicating that the program is exiting.





