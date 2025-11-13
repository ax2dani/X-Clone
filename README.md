# Chatter X 💬

Chatter X is a simple, frontend-only social media feed application, inspired by Twitter. It's built with vanilla JavaScript, HTML, and CSS, demonstrating core DOM manipulation and event handling concepts.

This project was created as part of the [Scrimba Fullstack Developer Path](https://scrimba.com/fullstack-path-c0fullstack).

## ✨ Features

  * **View Feed:** Renders a dynamic feed of tweets from a local data file (`data.js`).
  * **Post Tweet:** Users can write and post a new tweet, which gets added to the top of the feed using `unshift()`.
  * **Like/Unlike:** Click the heart icon to like a tweet. The count updates, the icon changes color, and the state is toggled.
  * **Retweet/Un-retweet:** Click the retweet icon to share a tweet. The count updates, the icon changes color, and the state is toggled.
  * **View Replies:** Expand or collapse the replies section for each tweet.
  * **UUID Generation:** Uses the `uuidv4` library to ensure all new tweets have a unique ID.
  * **Event Delegation:** Uses a single `document` event listener to efficiently manage all user interactions (`like`, `retweet`, `reply`).

## 💻 Tech Stack

  * **HTML5**
  * **CSS3**
  * **Vanilla JavaScript (ES6 Modules)**
  * **Vite:** Used as the development server and build tool.
  * **Font Awesome:** For icons.
  * **uuid:** To generate unique IDs for new tweets.

## 🚀 Getting Started

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Run the development server:
    ```bash
    npm start
    ```
5.  Open your browser and visit `http://localhost:5173` (or the URL provided by Vite).
