### Project Name: Authentication System

---

#### Description
This project is an authentication system built using Node.js, Express, and MongoDB. It allows users to register, login, submit secrets, and view secrets shared by other users.

---

#### Installation
1. Clone the repository.
2. Install dependencies by running `npm install`.
3. Create a `.env` file and add your database connection string.
4. Start the server by running `node app.js`.
5. Open your browser and visit `http://localhost:3000` to access the application.

---

#### Features
- Registration: Users can create an account by providing a username and password.
- Login: Registered users can log in to access their account.
- Submit Secrets: Logged-in users can submit their secrets.
- View Secrets: Users can view secrets shared by other users.

---

#### Technologies Used
- Node.js
- Express
- MongoDB
- EJS (Embedded JavaScript)
- Passport.js

---

#### Routes
- `/`: Home page.
- `/login`: Login page.
- `/register`: Registration page.
- `/secrets`: View shared secrets page.
- `/submit`: Submit secret page.
- `/logout`: Logs out the user.

---

#### Dependencies
- dotenv
- express
- ejs
- mongoose
- express-session
- passport
- passport-local-mongoose
- body-parser

---

#### Developer Notes
- The project uses sessions for user authentication and authorization.
- MongoDB is used to store user data such as username, password, and secrets.
- Passport.js is used for handling user authentication strategies.

---

#### Contributors
- Mohammad Salehi

---

#### License
This project is licensed under the MIT License.
