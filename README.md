# My Login App

This project is a simple web application that allows users to log in using their username and password. It consists of a login page and a workspace page where additional API routes can be added.

## Project Structure

```
my-login-app
├── src
│   ├── index.html          # The login page
│   ├── workspace.html      # The workspace page for additional API routes
│   ├── css
│   │   └── styles.css      # CSS styles for the application
│   └── js
│       ├── login.js        # JavaScript for handling login functionality
│       └── workspace.js     # JavaScript for the workspace page
├── package.json            # Configuration file for npm
└── README.md               # Documentation for the project
```

## Getting Started

To run this application, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd my-login-app
   ```

2. **Install dependencies** (if any):
   ```bash
   npm install
   ```

3. **Open the application**:
   Open `src/index.html` in your web browser to access the login page.

## Usage

- **Login Page**: Enter your username and password, then click the submit button to log in. The application will send a POST request to `https://localhost:7267/Usuario/login` with the provided credentials.

- **Workspace Page**: After logging in, you can navigate to `src/workspace.html` to access additional functionalities and API routes.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.