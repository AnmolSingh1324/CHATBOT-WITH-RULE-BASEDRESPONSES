# CHATBOT WITH RULE-BASED RESPONSES

## Project Overview
This is an advanced rule-based chatbot implemented as a single HTML file. It uses predefined patterns to detect user intents and generates appropriate responses based on those intents. This chatbot offers a smooth, modern UI with vibrant gradients and blur effects over a visually appealing background.

## Features
- Rule-based intent detection using regular expressions.
- Handles greetings, time queries, weather inquiries, farewells, thanks, and mood expressions.
- Personalized time-based greeting on first interaction.
- Prevents repeated user input responses.
- Modern and responsive chat interface with smooth scrolling.
- Accessible with ARIA labels for usability.

## How to Run
1. Open the `chatbot.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
2. Start chatting by typing messages into the input box and hitting the send button or pressing Enter.
3. The chatbot will respond based on detected intent.

## Technologies Used
- HTML5 with semantic elements.
- CSS3 for styling with gradients, flexbox, and backdrop filters.
- Vanilla JavaScript for chatbot logic and DOM manipulation.

## File Structure
- `chatbot.html` — the complete chatbot application with inline CSS and JavaScript.

## Usage
- Ask the chatbot greetings like "Hi" or "Hello".
- Inquire about the current time with keywords like "time".
- Say thank you to get polite responses.
- Talk about feelings, weather, or ask general questions.
- It will reply with predefined responses based on detected user intent.

## Customization
- Update responses in the JavaScript section under `this.responses` object.
- Modify intent patterns inside the `detect_intent` method to add or change recognized intents.

## Author
Created by Anmol Singh.

## License
This project is open for personal and educational use.

---
Enjoy chatting with your advanced rule-based chatbot!
