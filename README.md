  <h2 align="center">
    <samp>
      Netflix - A fully functional Netflix Clone made with MERN Stack and other technologies, check them below.
    </samp>
  </h2>


# Preview

<p align="center">
  <img src="netflix-ui/src/assest/loginMain.jpg"
     alt="Netflix Landing Page" >
</p>

<p align="center">
  <img src="netflix-ui/src/assest/landingMain.jpg"
     alt="Netflix Home Page" >
</p>
<p align="center">
  <img src="netflix-ui/src/assest/sliderMain.jpg"
     alt="Netflix Movies slider" >
</p>
<p align="center">
  <img src="netflix-ui/src/assest/genresMain.jpg"
     alt="Netflix Movies through diffrent genres" >
</p>
<p align="center">
  <img src="netflix-ui/src/assest/myListmain.jpg"
     alt="Netflix my list page" >
</p>



# Tech Stack

## BackEnd:

-    [Node.js](https://nodejs.org)
-    [Express.js](https://expressjs.com/)

## FrontEnd:

-    [React.js](https://reactjs.org/)

## DataBase:

-    [MongoDB](https://www.mongodb.com/)

# Usage

### Prerequisites:

The project can be used along side with the server side or without it untill the next Readme update .



-    Get a free API Key at [The Movie Database (TMDb)](www.themoviedb.org)

### Installation:

1. Clone the repo
     ```sh
     git clone https://github.com/Dev232-rock/NetflixClone
     ```
2. Enter your API Key in `.env.example.js`
     ```JS
     REACT_APP_API_KEY="Your TMDB API KEY GOES HERE"; "api key looks like 3024a22ed0f1c54e11ac7bb62cfea210"
     ```
3. Rename the `.env.example.js` to `.env.js`.

4. Install NPM packages
     ```sh
     cd netflix-ui
     npm install
     ```
5. Run the Server Side :
     ```sh
     cd netflix-api
     node server.js
     ```
