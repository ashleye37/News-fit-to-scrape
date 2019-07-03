# News-fit-to-scrape
Deployed Link: https://tranquil-retreat-93553.herokuapp.com/
Git Hub Pages Link: https://ashleye37.github.io/News-fit-to-scrape/ 

## Requirements
Whenever a user visits your site, the app should scrape stories from a news outlet of your choice and display them for the user. Each scraped article should be saved to your application database. 

Users should also be able to leave comments on the articles displayed and revisit them later. The comments should be saved to the database as well and associated with their articles. Users should also be able to delete comments left on articles. All stored comments should be visible to every user.

## Technologies Used
Express
Mongoose
Cheerio
Axios
Morgan

## Code Explanation / Demo
1. On page load any articles saved to the database will populate. 
2. When the user clicks "Scrape Articles" - any new articles which meet the minimum criteria will be populated. 
    - Minimum criteria: The article must have a Title, Link and Summary.
3. When the user clicks on any of the articles, a note form will populate and allow the user to add a note on that article. When they click save, the article will be populated to the database. The user can also update or delete the note as they like.
4. The user will then be able to click, "View All Notes" to see any notes left on the articles which have populated.