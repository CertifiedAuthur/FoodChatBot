## FoodChatBot

#### Overview
FoodChatBot is an intelligent chatbot designed to streamline the food ordering process. Built using Dialogflow, with a backend in Python and a MySQL database, this chatbot allows users to place orders, track order statuses, and manage their order lists with ease. Whether you're adding items to your order or removing them, FoodChatBot ensures a smooth and efficient experience.

###### Features
Order Placement: Collects and places your food orders seamlessly.
Order Tracking: Allows users to track the status of their orders in real-time.
Order Management: Users can add or remove items from their order list.
Delete Orders: Ensures that previous orders can be deleted when a new order is placed.

###### Getting Started
Prerequisites
Python 3.x
MySQL
Dialogflow account

###### Installation
Clone the Repository

bash
Copy code
git clone https://github.com/certifiedauthur/FoodChatBot.git
cd FoodChatBot

###### Install Dependencies

bash
Copy code
pip install -r requirements.txt

###### Set Up MySQL Database

Create a database named food_chatbot in MySQL.
Go to https://codebasics.io/resources/end-to-end-nlp-chatbot-project to download the database.

###### Configure Dialogflow

Import the Dialogflow agent provided in the dialogflow_agent directory.
Set up the intents and entities as per your requirements.

###### Run the Backend Server

bash
Copy code
python main.py
Usage
Placing an Order
Users can place new orders by specifying the food items they wish to order. The chatbot will collect the order details and store them in the database.

Adding Items to Order
If a user wants to add more items to an existing order, they can do so by specifying the items. The chatbot will update the order accordingly.

Removing Items from Order
Users can remove specific items from their order list. The chatbot will handle the request and update the order in the database.

Tracking Order Status
Users can check the status of their orders at any time. The chatbot will fetch the current status from the database and provide the user with the information.

Deleting Orders
When a user places a new order, any existing orders will be deleted to avoid confusion and ensure the new order is processed correctly.

###### Project Structure
bash
Copy code
FoodChatBot/
│
├── dialogflow_agent/         # Dialogflow agent configuration files
├── main.py                   # Main backend server file
├── requirements.txt          # Python dependencies
├── pandeyji_eatery.sql       # MySQL database
└── README.md                 # This README file

###### Contributing
We welcome contributions! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Thank you for using FoodChatBot! If you have any questions or need further assistance, please contact us at chibuzorauthur@gmail.com
