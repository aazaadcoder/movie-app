# Movie App

This project is a web application that allows users to search for movies and view trending titles. It leverages The Movie Database (TMDb) API for fetching movie data and Appwrite for backend services. The application is built using React and Vite, ensuring a fast and responsive user experience.

## Features

- **Search Functionality**: Users can search for movies by title, with results fetched from the TMDb API.
- **Trending Movies**: Displays a list of trending movies based on user search counts.
- **Loading Indicator**: Shows a spinner while data is being fetched to enhance user experience.
- **Error Handling**: Provides user-friendly error messages in case of API call failures.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Vite**: Next-generation frontend tooling for faster builds.
- **Appwrite**: Self-hosted backend-as-a-service platform providing APIs for authentication, databases, and more.
- **TMDb API**: Provides comprehensive movie data, including titles, descriptions, and images.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- TMDb API Key
- Appwrite instance

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/aazaadcoder/movie-app.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd movie-app
   ```

3. **Install dependencies**:

   Using npm:

   ```bash
   npm install
   ```

   Or using yarn:

   ```bash
   yarn install
   ```

4. **Set up environment variables**:

   Create a `.env` file in the root directory and add your TMDb API Key:

   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key
   ```

   Ensure you have an Appwrite instance running and configure the necessary environment variables for Appwrite as well.

### Running the Application

To start the development server, run:

```bash
npm run dev
```

This will launch the application, and you can access it at `http://localhost:3000/`.

## Project Structure

```
movie-app/
├── public/
│   └── hero-img.png
├── src/
│   ├── Components/
│   │   ├── LoadingSpinner.jsx
│   │   ├── MovieCard.jsx
│   │   └── Search.jsx
│   ├── App.jsx
│   ├── appwrite.js
│   └── main.jsx
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```

- **`public/`**: Contains static assets like images.
- **`src/`**: Contains the source code.
  - **`Components/`**: Reusable React components.
  - **`App.jsx`**: Main application component.
  - **`appwrite.js`**: Appwrite configuration and API calls.
  - **`main.jsx`**: Entry point for the React application.

## Deployment

The application is deployed using Vercel and can be accessed at:

[https://movie-app-one-eta-78.vercel.app/](https://movie-app-one-eta-78.vercel.app/)

To deploy your own version:

1. **Fork the repository** on GitHub.
2. **Connect the repository** to your Vercel account.
3. **Set environment variables** in Vercel for your TMDb API Key and Appwrite configuration.
4. **Deploy the application** through the Vercel dashboard.

## Acknowledgements

- [TMDb](https://www.themoviedb.org/) for providing the movie data API.
- [Appwrite](https://appwrite.io/) for backend services.
- [Vite](https://vitejs.dev/) for the build tool.
- [React](https://reactjs.org/) for the UI library.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project by submitting issues or pull requests. Your feedback is highly appreciated!

