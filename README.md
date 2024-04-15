**Chat App**

---

### Overview

This repository contains the source code for a chat app created using HTML, CSS, JavaScript, PHP, and MySQL. The app features a signup and login page, a chat interface, search functionality, and a section to view online users. Once logged in, users remain authenticated until they choose to log out. However, the app does not provide a "forgot password" feature or support file transfers; it solely facilitates text-based messaging.

### Features

- **Signup/Login:** Users can create accounts and log in securely.
- **Chat Interface:** Interactive interface for real-time messaging.
- **Search Bar:** Allows users to search for other users within the app.
- **Online Users:** Displays a list of users currently online.
- **Persistent Login:** Users stay logged in until they manually log out.
- **Security:** Implements secure authentication to prevent unauthorized access.

### Getting Started

To set up and run the chat app locally, follow these steps:

1. Clone this repository to your local machine.
2. Set up a local server environment (e.g., XAMPP, WAMP, MAMP) with PHP and MySQL support.
3. Import the provided SQL database schema to set up the necessary tables.
4. Configure the database connection in the PHP files to match your local environment.
5. Open the app in your web browser.
6. Sign up for a new account or log in with existing credentials.
7. Start chatting with other users!

### File Structure

```
chat-app/
│
├── index.php             # Main HTML file containing the chat interface
├── style.css             # CSS file for styling the app
├── javascript folder     # JavaScript folder containing javascript codes
├── php folder            # php folder containing php codes
├── login.php             # PHP script for user login
├── signup.php            # PHP script for user signup
├── search.php            # PHP script for user search
├── users.php             # PHP script to display online users
├── logout.php            # PHP script to log out user
├── config.php            # PHP script for database connection
├── chatapp.sql           # SQL file containing database schema
└── README.md             # Readme file providing information about the project
```

### Dependencies

- PHP
- MySQL
- Web server environment (e.g., Apache)

### Support

For any issues or questions regarding this project, please feel free to open an issue on GitHub.

### License

This project is licensed under the [MIT License](LICENSE).

### Acknowledgments

- Inspired by the need for a simple and secure chat application.
- Appreciation to contributors who helped improve this project.

---
**Note:** Customize the database connection details and adjust file paths as needed to match your local setup.
