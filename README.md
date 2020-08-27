# Restaurant-Booking-Chatbot

A goal oriented chatbot which parses information from user's responses using Natural Language Processing.

It first detects the intent of the user like greeting, goodbye, thanks etc. and then gives appropriate responses to user queries. After exchanging greetings, it asks for information required for booking a table in a restaurant. The required information includes:

*  Date
*  Time
*  Number of people
*  Restaurant name

Once it gets all the information, it makes a booking at that restaurant (currently parsing the information and saving it in key-value format which can be used with any API call).
