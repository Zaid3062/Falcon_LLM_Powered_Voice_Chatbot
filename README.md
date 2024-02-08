# Falcon_LLM_Powered_Voice_Chatbot
This repository contains the source code for a chatbot powered by the Falcon Language Model (LLM). The chatbot utilizes state-of-the-art natural language processing (NLP) techniques to understand and respond to user queries spoken in natural language

gtts: for text-to-speech conversion.
IPython.display: for displaying and playing audio in the notebook environment.
io: for handling in-memory file objects.
speech_recognition: for capturing voice input.
The text_to_speech() function converts text to speech using the gTTS library and plays the generated speech audio.

The get_voice_input() function captures voice input using the microphone. It uses the Recognizer class from the speech_recognition library to listen to audio input from the microphone and recognize speech using Google's speech recognition service.

The main code runs in a loop, continuously capturing voice input from the user using the get_voice_input() function.

If the user says 'exit', the loop breaks, and the program exits.

Otherwise, a placeholder response is generated (you can replace this with your actual bot's response processing logic), and it's printed as the bot's response.

The bot's response is then converted to speech using the text_to_speech() function and played back to the user.

The program ends with a message indicating that it's exiting.
