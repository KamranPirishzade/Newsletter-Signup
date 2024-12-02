# Newsletter Signup

A simple and responsive newsletter signup web application built with **HTML**, **CSS**, **Bootstrap**, **Node.js**, and **Mailchimp API** for managing subscribers.

## Features
- Responsive design using **Bootstrap**.
- Backend server powered by **Node.js** and **Express**.
- Integration with **Mailchimp API** to manage mailing lists.
- Success and failure feedback pages for users.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/newsletter-signup.git
   ```

2. Navigate to the project directory:
   ```bash
   cd newsletter-signup
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up your Mailchimp API key and audience ID:
   - Go to [Mailchimp](https://mailchimp.com/), log in, and create an API key.
   - Find your audience (list) ID from the Mailchimp dashboard.
   - Create a `.env` file in the project directory and add your API key and audience ID:
     ```env
     MAILCHIMP_API_KEY=your-api-key
     MAILCHIMP_AUDIENCE_ID=your-audience-id
     ```

5. Start the server:
   ```bash
   node app.js
   ```

6. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Project Structure

```
newsletter-signup/
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── images/
├── views/
│   ├── failure.html
│   ├── success.html
│   └── signup.html
├── app.js
├── .env
├── package.json
└── README.md
```

- **public/**: Contains static assets like CSS and images.
- **views/**: Contains HTML templates for the pages.
- **app.js**: Main application logic for the server.
- **.env**: Environment variables for API keys.

---

## Dependencies

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Body-parser](https://www.npmjs.com/package/body-parser)
- [Request](https://www.npmjs.com/package/request) (or `node-fetch` for modern API calls)

---

## Deployment

To deploy this project, you can use platforms like:
- [Heroku](https://heroku.com/)
- [Render](https://render.com/)

Make sure to set your environment variables in the hosting platform as well.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgements

This project is inspired by [Angela Yu's Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/).
