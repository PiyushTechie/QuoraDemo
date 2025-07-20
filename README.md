# Quora Demo

A simple Quora-inspired question and answer platform built with Node.js, Express, and EJS templating engine.

## 📋 Features

- **View Questions**: Browse through a collection of sample questions and answers
- **Question Display**: Clean, user-friendly interface to display questions with usernames
- **Sample Data**: Pre-loaded with example posts from different users
- **Responsive Design**: Clean and modern UI for optimal user experience

## 🛠️ Technologies Used

- **Backend**: Node.js, Express.js
- **View Engine**: EJS (Embedded JavaScript)
- **Styling**: CSS
- **HTTP Method Override**: For handling PUT/DELETE requests
- **UUID**: For generating unique identifiers

## 📁 Project Structure

```
REST_CLASS/
├── views/
│   ├── edit.ejs      # Edit post page
│   ├── home.ejs      # Homepage with all posts
│   ├── index.ejs     # Main index page
│   ├── new.ejs       # Create new post page
│   └── show.ejs      # Individual post view
├── index.js          # Main server file
├── package.json      # Dependencies and scripts
└── package-lock.json # Lock file
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v12 or higher)
- npm (Node Package Manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd REST_CLASS
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   node index.js
   ```
   or
   ```bash
   npm start
   ```

4. **Access the application**
   Open your browser and navigate to `http://localhost:8080`

## 📊 Sample Data

The application comes with pre-loaded sample posts from users like:
- **Anonymous**: "I love coding"
- **Shradha**: "Hard work is important to achieve success"
- **Rahul Kumar**: "I got selected for my first internship"

## 🔧 API Routes

- `GET /` - Homepage displaying all posts
- `GET /posts` - View all posts (redirects to index.ejs)

## 🎯 Current Functionality

- **Browse Posts**: View all questions and answers in a clean, organized layout
- **User Attribution**: Each post displays the username of the author
- **UUID Integration**: Uses UUID for unique post identification
- **Method Override**: Supports REST methods for future CRUD operations

## 🔮 Future Enhancements

- User authentication and registration
- Upvote/downvote system
- Comments on posts
- Search functionality
- User profiles
- Categories/tags for posts

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is for educational purposes. Feel free to use and modify as needed.

## 👨‍💻 Author

Created as a learning project to understand REST APIs and web development with Node.js and Express.

---

**Note**: This is a demo application created for learning purposes. It demonstrates basic web development concepts including server setup, templating, and data rendering.
