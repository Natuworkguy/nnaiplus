# NNAI Plus

NNAI Plus is a web-based AI chatbot interface with dark mode support, and local chat history.

## Features

- **Chatbot Interface**: Engage in conversations with an AI-powered chatbot.
- **Dark Mode**: Toggle dark mode for a better user experience.
- **Persistent Chat History**: Stores chat messages locally using `localStorage`.
- **Authentication Check**: Ensures users are logged in before accessing the chat.

## Installation

### Prerequisites

- A web server (e.g., Apache, Nginx, or a local development server)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/natuworkguy/nnaiplus.git
   cd nnai-plus
   ```
2. Place your API key in `info/api.key`.
3. Serve the site using a local or remote server.
4. Access `index.html` in a browser.

## Usage

1. Open the website in a browser.
2. If authentication is required, log in through the provided link.
3. Start chatting with the AI.
4. Toggle dark mode using the button in the top right corner.
5. Clear chat history with the plus (`+`) button.

## File Structure

```
NNAI Plus/
│── assets/              # Contains images and icons
│── index.html           # Main HTML file
│── manifest.json        # Web app manifest
│── info/api.key         # API key storage (not included in the repo)
│── styles.css           # Styling (if separated)

```

## Technologies Used

- **HTML, CSS, JavaScript** for front-end development.

- **LocalStorage** for chat history persistence.

## Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the AGPL-3.0 License.

## Contact

For issues or feature requests, open an issue in the repository or contact info\@nathannetwork.com.

