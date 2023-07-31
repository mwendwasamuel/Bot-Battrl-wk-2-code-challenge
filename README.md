**Bot Battlr Web App**

Welcome to Bot Battlr, the one and only spot in the known universe where you can custom build your own Bot Army! This is our web app that allows you to browse through a list of robots, view a robot's details, and enlist bots into your army.
Getting Started

To get started with the project, follow these steps:

    Clone the repository from GitHub.
    Install the required dependencies using npm install.
    Create a db.json file in the project directory and populate it with the bot data. You can use the provided sample data or add your own.
    Start the backend server by running the following command: json-server --watch db.json.
    Test the server by visiting this route in the browser: http://localhost:8001/bots.

Core Features

As a user, you can:

    See profiles of all bots rendered in BotCollection.
    Add an individual bot to your army by clicking on it. The selected bot will render in the YourBotArmy component. The bot can be enlisted only once, and it does not disappear from the BotCollection.
    Release a bot from your army by clicking on it. The bot will disappear from the YourBotArmy component.
    Discharge a bot from their service forever by clicking the red button marked "x", which will delete the bot both from the backend and from the YourBotArmy on the frontend.

Endpoints
GET /bots
Feel free to explore the application and customize your Bot Army to your liking! 