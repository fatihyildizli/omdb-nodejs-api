# omdb-nodejs-api
[![GitHub stars](https://img.shields.io/github/stars/fatihyildizli/omdb-nodejs-api.svg)](https://github.com/fatihyildizli/omdb-nodejs-api/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/fatihyildizli/omdb-nodejs-api.svg)](https://github.com/fatihyildizli/springboot-tesseract-ocr/network/members)
[![Total Downloads](https://img.shields.io/packagist/dt/fatihyildizli/somdb-nodejs-api.svg?style=flat-square)](https://packagist.org/packages/fatihyildizli/omdb-nodejs-api-ocr)
![License](https://img.shields.io/github/license/fatihyildizli/omdb-nodejs-api)
![Code size](https://img.shields.io/github/repo-size/fatihyildizli/omdb-nodejs-api)
![Top Language](https://img.shields.io/github/languages/top/fatihyildizli/omdb-nodejs-api)
![Languages](https://img.shields.io/github/languages/count/fatihyildizli/omdb-nodejs-api)
![Views](https://img.shields.io/github/search/fatihyildizli/omdb-nodejs-api/omdb-nodejs-api)

OMDB nodejs Rest API | Movie search, movie details |  http://www.omdbapi.com/

**Run project**
`node server.js`

**Change Apikey**

`const omdbApiKey=   'OMDB_SECRET_API_KEY';`


**How to get an API KEY ?** 

http://www.omdbapi.com/apikey.aspx 


**Sample Requests:**


**Request:** http://localhost:8888/search/?q=batman

**Response:**

`"Search": [
    {
      "Title": "Batman Begins",
      "Year": "2005",
      "imdbID": "tt0372784",
      "Type": "movie",
      "Poster": "https://m.media-amazon.com/images/M/MV5BZmUwNGU2ZmItMmRiNC00MjhlLTg5YWUtODMyNzkxODYzMmZlXkEyXkFqcGdeQXVyNTIzOTk5ODM@._V1_SX300.jpg"
    },  {
    ...
    }
    ]`


**Request:** http://localhost:8888/getmoviedetail/?id=tt0372784

**Response:**

`{
  "Title": "Batman Begins",
  "Year": "2005",
  "Rated": "PG-13",
  "Released": "15 Jun 2005",
  "Runtime": "140 min",
  "Genre": "Action, Adventure",
  "Director": "Christopher Nolan",
  "Writer": "Bob Kane (characters), David S. Goyer (story), Christopher Nolan (screenplay), David S. Goyer (screenplay)",
  "Actors": "Christian Bale, Michael Caine, Liam Neeson, Katie Holmes",
  "Plot": "After training with his mentor, Batman begins his fight to free crime-ridden Gotham City from corruption.",
  "Language": "English, Mandarin",
  "Country": "USA, UK",
  "Awards": "Nominated for 1 Oscar. Another 14 wins & 72 nominations.",
  "Poster": "https://m.media-amazon.com/images/M/MV5BZmUwNGU2ZmItMmRiNC00MjhlLTg5YWUtODMyNzkxODYzMmZlXkEyXkFqcGdeQXVyNTIzOTk5ODM@._V1_SX300.jpg",
  "Ratings": [
    {
      "Source": "Internet Movie Database",
      "Value": "8.2/10"
    },
    {
      "Source": "Rotten Tomatoes",
      "Value": "84%"
    },
    {
      "Source": "Metacritic",
      "Value": "70/100"
    }
  ],
  "Metascore": "70",
  "imdbRating": "8.2",
  "imdbVotes": "1,234,942",
  "imdbID": "tt0372784",
  "Type": "movie",
  "DVD": "18 Oct 2005",
  "BoxOffice": "$204,100,000",
  "Production": "Warner Bros. Pictures",
  "Website": "N/A",
  "Response": "True"
}`



**Documentation:**

http://www.omdbapi.com/#usage

