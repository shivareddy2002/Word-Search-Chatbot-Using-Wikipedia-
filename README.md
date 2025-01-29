# Word-Search-Chatbot-Using-Wikipedia
<img width="278" alt="image" src="https://github.com/user-attachments/assets/c9e79365-bc9d-4468-be03-61aea052b0c4" />

Project Overview

PICTOPEDIA is a chatbot that allows users to search for information on specific words or terms using the Wikipedia API. The application serves as an interactive word search tool where users can input queries and receive relevant information in response.

Key Features
User-Friendly Interface: The chatbot features a simple and interactive UI with an input field for user queries and a search button to trigger responses.
Real-Time Information Retrieval: Fetches content directly from Wikipedia using API calls, ensuring accurate and comprehensive information.
Dynamic Chat Output: Displays search results in a chat-style format, enhancing user experience.
Technologies Used
HTML, CSS: For the frontend structure and styling.
JavaScript: Handles user input and integrates API calls for dynamic content rendering.
Wikipedia API: Provides a robust backend for fetching word definitions and related information.
The flow of the PICTOPEDIA: Word Search Chatbot Using Wikipedia API project can be outlined as follows:

1. User Input
The user interacts with the chatbot by typing a query or word in the input field.
Example query: "What is Artificial Intelligence?"
2. Input Handling
When the user presses the Search button, an event handler function (handleUserInput()) is triggered in the script.js file.
The user's input is validated (checked for empty input).
3. API Request
The chatbot constructs a request to the Wikipedia API using the user's query.
The request fetches relevant data in JSON format from Wikipedia, such as the introduction or key information about the searched term.
4. Processing Response
The data received from Wikipedia is parsed to extract the necessary information.
Error handling is included for cases where no data is found or when the query is invalid.
5. Displaying Results
The chatbot dynamically updates the chat output area to display the response fetched from the Wikipedia API.
If the search is successful, it shows the relevant content in a user-friendly format.
If the search fails, it provides an appropriate error message (e.g., "Sorry, no information found for this word.").
6. User Interaction Loop
The chatbot allows the user to perform multiple searches by repeating steps 1-5.
It retains the chat history during the session to maintain conversation context.
Flow Summary
User Input ➡️ Input Handling ➡️ API Request ➡️ Response Processing ➡️ Display Results ➡️ Repeat Interaction
