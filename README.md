# mongoDB
first create four folders 
models
nodeModels
public view 
the package .json file 
I'll also need a server.js file
the server.js file will require
all 6 packages
express, express-handlebars,mongoose,body-parser,cheerio,request
then I must connect this app to handlebars layout
the layout must be explained more the view and public must be seperated or parsed using express
after that it is time to make connections
mongoose must be connected to the local host so that the news and comments will display on the page.
now i have to GET the articles and tell them where to go ( Retrieve data from the db)
This means i'm ready to scrape 
 Scrape data from one site and place it into the mongodb db
  Load the html body from request into cheerio
    For each element with a "article" class
     Save the text and href of each link enclosed in the current element
     Insert the data in the scrapedData db
       Send a "Scrape Complete" message to the browser
 Listen on port 3000





