# React Redux Pagination and Filtering Project

## 📌 Project Overview
This is a React-Redux project implementing pagination, searching, and filtering functionalities. The project fetches posts from an API, allows users to search for posts by title or content, and filter them by user. It includes smooth pagination and a detailed post view.

## 🚀 Features
- **Dynamic Pagination**: Navigate through posts using next/previous buttons and page numbers.
- **Search Functionality**: Search posts by title or content in real-time.
- **User Filtering**: Filter posts by user ID.
- **Post Details Page**: View full details of a selected post, including comments.
- **Loading Spinner**: Displays while fetching data.
- **Error Handling**: Handles API errors gracefully.

## 🛠️ Tech Stack
- **Frontend**: React.js, Redux Toolkit
- **State Management**: Redux, React-Redux
- **Routing**: React Router
- **Styling**: CSS
- **API**: JSONPlaceholder (https://jsonplaceholder.typicode.com)

## 📂 Project Structure
```
📁 src/
 ┣ 📁 components/
 ┃ ┣ 📄 LoadingSpinner.jsx
 ┃ ┣ 📄 Pagination.jsx
 ┃ ┣ 📄 PostDetails.jsx
 ┃ ┗ 📄 PostList.jsx
 ┣ 📁 features/
 ┃ ┗ 📄 postSlice.js
 ┣ 📁 store/
 ┃ ┗ 📄 store.js
 ┣ 📄 App.jsx
 ┣ 📄 index.js
 ┣ 📄 App.css
 ┗ 📄 README.md
```

## 🏗️ Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-project-name
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open in your browser at `http://localhost:3000`.

## ⚙️ How It Works
- The `PostList` component fetches posts and renders them with pagination.
- The `Pagination` component manages page navigation.
- The `PostDetails` component fetches and displays details of a selected post.
- The `postSlice.js` file manages Redux state.
- The `store.js` configures the Redux store.

## 💡 Future Enhancements
- Add sorting options (e.g., sort by date, popularity).
- Implement infinite scrolling.
- Improve UI/UX with animations.

## 🤝 Contributing
Feel free to fork this repository and submit a pull request with your improvements! 😊

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
