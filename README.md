# Chat App with Flet

A real-time chat application built using Python and the Flet framework.

## About

This repository contains a simple chat application built using Python and the Flet framework. Flet is a Python framework for building web, mobile, and desktop applications using a single codebase. This chat app demonstrates the capabilities of Flet in building a real-time communication platform.

## Features

* Real-time messaging: Send and receive messages in real-time
* User authentication: Login and register users to access the chat app
* Chat rooms: Create and join chat rooms to communicate with others
* User presence: See who's online and offline in real-time

## Getting Started

### Prerequisites

* Python 3.7 or later
* Flet framework (install using `pip install flet`)

### Running the App

1. Clone the repository: `git clone https://github.com/boshuua/Chat-App.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Direct the directory to look at the .venv folder `.venv\Scripts\activate`
4. Run the app: `flet run --web <the directory used to store git repo>`
5. App should run in the browser automatically 

## How it Works

The app uses Flet's WebSocket API to establish real-time communication between clients. When a user sends a message, the app broadcasts the message to all connected clients in the same chat room. The app also uses Flet's built-in authentication and authorization features to manage user sessions and access control.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.

## Acknowledgments

* Flet framework: [https://flet.dev](https://flet.dev)
* Python: [https://www.python.org](https://www.python.org)
