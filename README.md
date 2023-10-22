
# FilmPire

## Overview

FilmPire is a film description application that I built using React.js, Redux, MaterialUI, AlanAI, and IMDB's API. It provides users with detailed information about films, including cast, crew, ratings, and more. Additionally, the application features user authentication to enhance the user experience.

## Features

- **Film Information**: Get detailed information about films, including cast, crew, release year, ratings, and more.
- **User Authentication**: Allow users to create accounts and log in to personalize their experience and save their favorite films.
- **Search Functionality**: Easily search for specific films based on title, genre, or keywords.
- **Intuitive UI/UX**: The user interface is designed to be user-friendly, ensuring smooth navigation and accessibility.
- **AlanAI Integration**: Incorporates AlanAI for voice-enabled interactions, providing an additional layer of convenience for users.

## Optimization: 
- Implement SSR with frameworks like Next.js to pre-render pages on the server, improving initial load times.
- Use tools like Webpack Bundle Analyzer to identify large dependencies and optimize the bundle size.
- Compress and serve images in next-gen formats like WebP for faster loading.

## Lessons Learned:

- Implementing Redux for state management in FilmPire improved my understanding of global state and actions in complex applications.
- Integrating MaterialUI components enhanced my knowledge of UI libraries and their customization capabilities.
- Incorporating AlanAI for voice interactions expanded my skill set to include AI integration in web applications.



## Technologies Used

- ![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
- ![Redux](https://img.shields.io/badge/-Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
- ![MaterialUI](https://img.shields.io/badge/-Material_UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white)
- ![AlanAI](https://img.shields.io/badge/-Alan_AI-2A1D6E?style=for-the-badge&logo=alan&logoColor=white)
- ![IMDB](https://img.shields.io/badge/-IMDB_API-FF9900?style=for-the-badge&logo=imdb&logoColor=white)

## Usage

To run the Filmpire application, follow these steps:

1. Clone this repository
    ```bash
    git clone https://github.com/brishy/filmpire_brishy.git
    cd filmpire_brishy
    ```

2. Install dependencies
    ```bash
    npm install
    ```

3. Copy the example environment file
    ```bash
    cp .env.example .env
    ```

4. Run the app
    ```bash
    npm run dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.
