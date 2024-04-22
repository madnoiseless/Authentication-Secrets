# Project README

This project is a simple web application that allows users to register, login, and access a secrets page. The application utilizes Node.js with the Express framework for the backend, MongoDB as the database, and EJS for templating.

### Prerequisites
Before running the application, make sure you have the following installed:
- Node.js
- MongoDB

### Getting Started
1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Create a `.env` file in the root directory and add your secret key:
   ```
   SECRET=your_secret_key_here
   ```
4. Start your MongoDB server.
5. Run `node app.js` to start the application.

### Features
- **Home Page:** Accessible at the root URL ("/"), it serves as the landing page.
- **Login Page:** Visit "/login" to log in with your credentials.
- **Registration Page:** Visit "/register" to create a new user account.
- **Secrets Page:** Once logged in, users can access the secrets page.

### Dependencies
- dotenv
- express
- body-parser
- ejs
- mongoose
- mongoose-encryption

### Usage
1. Visit the application on `http://localhost:3000`.
2. Register a new account or login with existing credentials.
3. Access the secrets page after successful authentication.

### Security
- User passwords are encrypted in the database using the `mongoose-encryption` plugin.

### Contributions
Contributions are welcome. Feel free to fork the repository, make changes, and submit a pull request.

### License
This project is licensed under the MIT License.