 
## Number Guessing Game
    This project is a game in which the user has to guess a secret number between 1 and 10. The player has 5 attempts to guess the number correctly. If they run out of tries or guess the number, the game stops.
## Main features:
    Random generation of a secret number between 1 and 10.
    5 attempts to guess the number.
## Technologies used
    Node.js: Execution environment 
    JavaScript: Programming language 
    HTML: For the user interface.
    CSS: For the visual design of the application.
## Project structure
    The basic structure of the project is as follows:
    /my-guess-game
    │
    ├── /public.
    │  └── index.html # HTML file containing the game view.
    │  └── script.js # Server logic and Express configuration.
    │
    ├─── Dockerfile # Configuration to create the Docker image.
    ├─── package.json # Project dependencies and NPM scripts.
    └─── README.md # This README file.
## Prerequisites.
Make sure you have the following tools installed on your machine:
Node.js: Download and install Node.js.
## Installation
1. Clone the repository
First, clone this repository on your local machine using Git:
    git clone https://github.com/Cristina-Colcha/Adivinanza.git
2. Install dependencies
Access the project folder and run the following command to install the Node.js dependencies:
    cd my-guess-game
    npm install
3. Run the application in development
To run the application locally, you can use the following command:
    npm start
This will start a server at http://localhost:3000 and you will be able to access the game from your browser.
## Usage
Open your browser and go to http://localhost:3000.
    The game will display a field to enter a number between 1 and 10.
    Enter a number and click on “Guess”.
    The game will give you clues as to whether the number is too low or too high.
    If you guess the number or run out of tries, the game will stop.
## Contribution
If you wish to contribute to this project, please follow these steps:
1. Make a fork of the repository.
2. Create a new branch for your feature (git checkout -b feature/my-new-feature).
3. Make your changes and commit (git commit -am 'Added my new feature').
4. Push to your branch (git push origin feature/my-new-feature).
5. Open a pull request.
## If you want to use the Docker Hub image:
    Download image from Docker Hub:
    The container is configured to run on port 3000 you can use the image with the following message

    docker pull cristinacolcha/mi-juego-adivinanza:latest

This README is organized in a single block with all the detailed information, and each section is clearly described for quick understanding.

