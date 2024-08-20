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

1. Clone the repository: `git clone https://github.com/your-username/chat-app-flet.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the app: `python app.py`
4. Open the app in your web browser: `http://localhost:5000`

## How it Works

The app uses Flet's WebSocket API to establish real-time communication between clients. When a user sends a message, the app broadcasts the message to all connected clients in the same chat room. The app also uses Flet's built-in authentication and authorization features to manage user sessions and access control.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments

* Flet framework: [https://flet.dev](https://flet.dev)
* Python: [https://www.python.org](https://www.python.org)
