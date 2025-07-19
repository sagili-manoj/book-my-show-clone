# BookMyShow Clone
Welcome to the BookMyShow Clone project! This is a React-based web application that mimics the functionality of the popular ticketing platform, BookMyShow. It includes multiple components, a payment integration (test mode), and uses APIs to fetch movie data.

## Live Demo
[🚀Click here to view the live project](https://sagilimanoj-bookmyshow-clone.netlify.app/)

## Features
- **Movie Display**: Displays movies and their details using the TMDB API.
- **Top-Rated Movies**: Displays a list of top-rated movies.
- **Payment Integration**: Test-mode payment functionality using Razorpay.
- **Responsive Design**: The app is designed to work seamlessly on various screen sizes.

## Important Notes
- **Payment is in Test Mode**: Do not use real payment details. Use Razorpay's test credentials for payment simulation.
- **API Limitations**: Some images or data may not load due to API restrictions or rate limits.
- **Missing Functionalities**: Search functionality and user authentication are not implemented yet.

## How to Run the App
Follow these steps to set up and run the project on your local machine:

### Prerequisites
- Node.js and npm installed on your machine.
- A code editor (e.g., Visual Studio Code).

### Steps
#### Clone the Repository:
```bash
git clone https://github.com/sagili-manoj/book-my-show-clone.git
cd book-my-show-clone
```

#### Install Dependencies:
Install all the required dependencies using npm:
```bash
npm install
```

#### Start the Application:
Run the app in development mode:
```bash
npm start
```
The app will open in your default browser at `http://localhost:3000`.

## Project Structure
Here’s a brief overview of the project structure:
```plaintext
book-my-show/
├── public/              # Static assets
├── src/                 # Source code
│   ├── components/      # Reusable components
│   │   ├── Cast/        # Cast related components
│   │   ├── Entertainment/ # Entertainment related components
│   │   ├── HeroCarousel/ # Hero carousel components
│   │   ├── MovieHero/   # Movie hero section components
│   │   ├── Navbar/      # Navigation bar components
│   │   ├── PaymentModal/ # Payment modal components
│   │   ├── PlayFilters/ # Play filters components
│   │   ├── Poster/      # Poster components
│   │   └── PosterSlider/ # Poster slider components
│   ├── context/         # Context providers
│   │   └── Movie.context.js # Movie context
│   ├── layout/          # Layout components
│   │   ├── Default.layout.js # Default layout
│   │   └── Movie.layout.js # Movie layout
│   ├── pages/           # Main pages of the app
│   │   ├── Home.page.js # Home page
│   │   ├── Movie.page.js # Movie page
│   │   └── Play.page.js # Play page
│   ├── App.css          # Main CSS file
│   ├── App.js           # Main application component
│   ├── index.css        # Global styles
│   └── index.js         # Entry point
├── .gitignore           # Specifies files to ignore in Git
├── package-lock.json    # Lock file for dependencies
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## API Keys and Endpoints
To fetch movie data, the app uses The Movie Database (TMDB) API. Below are the API details:

### API Key:
```plaintext
API_KEY=3f613ae2d81a6a8bbaf8c27937c8ce7a
```

### Search for Movies (e.g., Avengers):
```plaintext
https://api.themoviedb.org/3/search/movie?api_key=3f613ae2d81a6a8bbaf8c27937c8ce7a&query=Avengers
```

### Top-Rated Movies:
```plaintext
https://api.themoviedb.org/3/movie/top_rated?api_key=3f613ae2d81a6a8bbaf8c27937c8ce7a&language=en-US&page=1
```

## Missing Functionalities
- **Search Functionality**: The ability to search for movies is not yet implemented.
- **User Authentication**: User login and registration features are not included.

## Contributing
If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b origin/feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin origin/feature-name
   ```
5. Open a pull request.

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- **TMDB API**: For providing movie data.
- **Razorpay**: For payment integration in test mode.
