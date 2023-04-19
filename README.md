KISMET-GPT
Introduction: 
Kismet is a chatbot designed to interact with you and provide assistance in various tasks. With my advanced artificial intelligence and natural language processing capabilities, I can understand your questions and respond with helpful information, advice, or guidance. Whether you need help with a specific task or just want to chat, its there for you 24/7. So, feel free to ask anything!

Features: 
1. 24/7 Availability: Kismet is always available to assist users, regardless of their location or time zone.
2. Personalized: Kismet is a personalized chatbot designed to meet the specific needs of each user. By collecting information about the user's preferences and behavior, Kismet provides more targeted and relevant responses.
3. Context Awareness: Kismet has the ability to understand the context of the conversation and generate responses based on the previous messages in the conversation.
4. Open-Ended Conversations: Kismet can engage in open-ended conversations, enabling users to explore different topics and have more meaningful interactions.
5. Versatility: Kismet can be used for various applications, such as customer service, education, entertainment, and more.


API Integration: 

1. Created an OpenAI account and got an API key: Signed up for OpenAI and obtained an API key that allowed me to access the API endpoints.
2. Imported the OpenAI package and configured the API key: In my Flask app, imported the openai package and configured it with my API key. All this was done aiapi.py file
3. Took the input as a question from the user and sent it to the OpenAI API for processing. The input was taken from index.html file and passed on to app.py which sends it to aiapi.py for processsing
4. aiapi.py processes the input and sends the output in the json format to app.py
5. app.py takes the output and displays it to the user with the help of index.html

