# project-mode


Project Idea

Build a website that display everyday 10 best movies to watch that users liked.

Planning

As a user I have to access to a list of movies and be able to filter by genre, date, country, rating
As user also I have right to rate the movie and add a comment.

Api to use

fetch("https://movies-tvshows-data-imdb.p.rapidapi.com/?type=get-movies-by-title&title=matrix", {
    "method": "GET",
    "headers": {
        "x-rapidapi-key": "SIGN-UP-FOR-KEY",
        "x-rapidapi-host": "movies-tvshows-data-imdb.p.rapidapi.com"
    }
})
.then(response => {
    console.log(response);
})
.catch(err => {
    console.error(err);
});
