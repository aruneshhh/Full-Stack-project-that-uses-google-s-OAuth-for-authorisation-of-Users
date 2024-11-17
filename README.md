
# Secrets Project

A web application that allows users to securely share their secrets. This project demonstrates modern web development practices including secure user authentication and session management.

## Features

- **User Authentication**: 
  - Local authentication with hashed passwords (bcrypt).
  - OAuth2 integration with Google.

- **Session Management**: 
  - Secure sessions using `express-session`.

- **Database**: 
  - Secrets stored securely in PostgreSQL.

- **Templating**: 
  - Dynamic rendering using EJS.

## Technologies Used

- **Backend**: Node.js with Express.js
- **Frontend**: EJS templates
- **Database**: PostgreSQL
- **Authentication**: Passport.js (Local & Google OAuth2)
- **Security**: bcrypt for password hashing, environment variables for sensitive information

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Environment Variables**:
   Create a `.env` file in the root directory with the following variables:
   ```env
   GOOGLE_CLIENT_ID=<Your Google Client ID>
   GOOGLE_CLIENT_SECRET=<Your Google Client Secret>
   SESSION_SECRET=<Your Secret Key>
   PG_USER=<Your PostgreSQL User>
   PG_HOST=<Your Database Host>
   PG_DATABASE=<Your Database Name>
   PG_PASSWORD=<Your Database Password>
   PG_PORT=<Your Database Port>
   ```

4. **Database Setup**:
   Ensure PostgreSQL is installed and running. Create the required database schema.

5. **Run the Application**:
   ```bash
   node index.js
   ```
   The application will run on `http://localhost:3000`.

## Scripts

- **Start Server**:
  ```bash
  node index.js
  ```

## Dependencies

The project uses the following dependencies:
- bcrypt
- body-parser
- dotenv
- ejs
- express
- express-session
- passport
- passport-google-oauth2
- passport-local
- pg

## License

This project is licensed under the ISC License.

---

Let me know if you need any further assistance!
