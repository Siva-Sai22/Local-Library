# Node.js Local Library

**Live Demo:** [https://handsome-precious-boysenberry.glitch.me]

This is a simple local library website built with Node.js and Express.

## Project Structure

- `app.js`: The main application file.
- `bin/www`: The script that starts the server.
- `controllers/`: Contains controller scripts for handling different routes.
- `models/`: Contains Mongoose schemas and models for the different data entities.
- `public/`: Contains static files like stylesheets and images.
- `routes/`: Contains scripts for handling different routes.
- `views/`: Contains Pug templates for generating the HTML pages.
- `populatedb.js`: A script for populating the database with initial data.

## Getting Started

1. Clone the repository.
2. Install dependencies with `npm install`.
3. Create a .env file in the root directory of the project and replace mongodb_uri with your MongoDB database's connection string.
4. Start the server with `npm start`.
5. Visit `http://localhost:3000` in your web browser.

## Dependencies

- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [Pug](https://pugjs.org/)

## License

This project is licensed under the MIT License.