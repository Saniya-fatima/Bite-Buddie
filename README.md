# Bite-Buddie

Welcome to the Bite Buddie Dialogflow project repository! This project utilizes Dialogflow to create a chatbot for handling food delivery orders. Below, you'll find information on how to set up and use the project.

![Screenshot 2024-07-11 182407](https://github.com/Saniya-fatima/Bite-Buddie/assets/122198174/2d83d3bf-0f17-4d1f-bd67-007356317504)

![Screenshot 2024-07-11 182421](https://github.com/Saniya-fatima/Bite-Buddie/assets/122198174/f1ae1612-6b5c-478e-8695-9efbddeb69ed)

## Intents

This project includes several intents designed to manage food orders and tracking:

- **Default Fallback Intent**: Handles unrecognized user inputs.
- **Default Welcome Intent**: Greets users when they start interacting with the bot.
- **new.order**: Initiates a new food order.
- **order.add** (context: ongoing-order): Adds items to an ongoing order.
- **order.complete** (context: ongoing-order): Completes the current order.
- **order.remove** (context: ongoing-order): Removes items from an ongoing order.
- **track order** (context: ongoing-tracking): Tracks the status of an order.

Each intent serves a specific function in guiding users through the food ordering process.

## Setup Instructions

To set up this project locally or integrate it into another environment, follow these steps:

1. **Dialogflow Agent Setup**:
   - Import the provided ZIP file into your Dialogflow console to recreate the agent configuration.

2. **Integration Setup**:
   - Ensure your integration platform (e.g., web, mobile) is configured to communicate with Dialogflow.
   - Update necessary credentials or API keys in your integration code.

3. **Testing and Deployment**:
   - Test the bot extensively to ensure all intents and functionalities work as expected.
   - Deploy the bot to your preferred platform or test environment.

## Usage

Once deployed, users can interact with the bot using natural language to place, modify, or track their food orders. Ensure the bot provides clear prompts and handles user inputs gracefully.



