# Pizza Order Service Chat Bot

This is a simple command-line-based Customer Service Chatbot that can help users place orders for pizza. It interacts with the user to determine their choice of pizza, delivery address, payment method, and confirmation of the order.

## Getting Started

To use this chat bot, follow the steps below:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/prashantkparth/chatbot.git
```

2. Navigate to the project directory:

```bash
cd chatbot
```

3. Run the Python script:

```bash
python chatbot.py
```

## Usage

The chat bot will welcome the user and ask what type of cuisine they are in the mood for. In this version, it specifically deals with pizza orders. The user can interact with the bot by typing messages. Here's a sample conversation:

```
     !!     Welcome to Customer Service Chatbot     !!
Hi there! What type of cuisine are you in the mood for today?

You: I want pizza

Bot: Today we have a special #deal# for you.

    You can get two large pizzas for the price of one. Would you like to take advantage of that offer?

     1.Pizza Margherita
     2.Quick Tomato Pizzas
     3.Four Cheese Pizza
     4.Cheesy Vegetable Pizza
     5.Tandoori Paneer Pizza
     6.Thin Crust Hawaiian Pizza
     7.Uttapam Pizza
     8.Chocolate Pizza
     9.Onion Pizza
     10.Veggie pizza

    Which type of Pizza are you in the mood for today?
               Please type the menu number

You: 1 and 7

Bot: Pizza Margherita and Uttapam Pizza, Wonderful choice! Can I have your delivery address, please?

You: Mfp, India

Bot: Thank you! Your order will be delivered to Mfp, India. May I have your phone number for any delivery updates?

You: 123456

Bot: Thank you! Your order for one Pizza Margherita and one Uttapam Pizza will be delivered to Mfp, India.
                        Your total is Rupee 350. Will you be paying with cash or UPI?

You: UPI

Bot: Great! I'll send UPI ID for payment. UPI: xxxx2154@xx 
              If payment will done please type 'ok'.

You: ok

Bot: Thank you for payment. Your order is confirmed, and you should receive it in about 30-40 minutes. Is there anything else I can assist you with?

You: That's all, thank you

Bot: You're welcome! Enjoy your meal, and if you have any other questions in the future, feel free to reach out. 
             !!  Have a great day  !! 
                Please type 'exit'
```

The user can type 'exit' at any time to end the conversation.
