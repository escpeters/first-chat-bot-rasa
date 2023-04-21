# first-chat-bot-rasa
This is a chatbot built with Rasa and Python. Its function is to converse with user and determine the time zone of interest to the user. It is a good starting point for anyone interested in developing a very introductory chatbot.

## Limitations
1. In its current form, the chat bot simply chats with the user to determine which city the user wants the time zone for. That chat bot looks up cities in a very limited directory and returns the time zone of the city. More robust version of this in production could utilize utilize an API to determine the time zone. This change would be made in the actions.py file.

2. Few training examples were provided for the stories which can result in the chat bot having unexpected responses to the conversation. This change would need to be reflected in the stories.ml and the nlu.ml files. 

3. Additional responses, responses and slots can be added by updating the domain.yl file. 
