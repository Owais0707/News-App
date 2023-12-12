# News-Website
Its a website that displays latest news on any topic fetching various news data from new-api server.
The data is fetched using api from newapi.org server.
News API is a simple HTTP REST API for searching and retrieving live articles from all over the web.


Index.html file-
It contains all the html code for the frontend of our website to display. Basically it contains 
1- The navbar
2- The main section which display multiple card clones with news heading, image, and body content of the news.


Style.css file-
It contains all the css code needed to design our website

Script.js file-
Here our javascript does what is called behind the seen task which are as follows:
1- It fectches the the data from newapi.org server.
2-It then binds the data and fills it inside the card clones(built using html and css) using document object model and various user defined functions like binddata() and filldatainsidecard().
3-It then renders our frontend using DOM(Document Object Model)

