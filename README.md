# Feedback App

A React-based application for collecting and managing user feedback. The app allows users to add, edit, and delete feedback with a focus on simplicity and ease of use.

---

## Features

- View feedback list with user ratings and comments.
- Add new feedback with customizable ratings and text.
- Edit or delete existing feedback.
- Real-time data handling powered by a JSON server.
- Stylish UI built with React and modern libraries.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/feedback-app.git
   cd feedback-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the JSON server:

   ```bash
   npm run server
   ```

4. Start the React development server:

   ```bash
   npm start
   ```

5. Run both servers concurrently:
   ```bash
   npm run dev
   ```

## Usage

1. Open the app in your browser at http://localhost:3000.
2. Use the UI to add, edit, or delete feedback.
3. Feedback data is served from a local JSON server, running at http://localhost:5000/feedback.

## Project Structure

```bash
feedback-app/
├── public/                # Static assets
├── src/
│   ├── components/       # Reusable React components (Header, FeedbackForm, FeedbackList, etc.)
│   ├── context/         # Context API for state management
│   ├── data/           # Static feedback data (used for testing)
│   ├── App.js         # Main app component
│   └── index.js       # Entry point
├── db.json            # JSON server database
├── package.json       # Project metadata and dependencies
└── README.md         # Project documentation
```

## API Endpoints

- GET /feedback: Retrieve all feedback.
- POST /feedback: Add new feedback.
- PUT /feedback/:id: Update feedback by ID.
- DELETE /feedback/:id: Delete feedback by ID.

## Development Scripts

- npm start: Start the React development server.
- npm run server: Start the JSON server.
- npm run dev: Start both servers concurrently.
