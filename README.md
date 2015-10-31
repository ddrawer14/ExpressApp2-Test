
## ExpressApp2 - C9 development

 Single page application which works without a single page refresh. Eliminate the need for page refreshing or visiting separate URIs entirely.
 
 - Store and retrieve JSON data in a MongoDB collection using HTTP POST and HTTP GET
 - Remove data from the collection using HTTP DELETE
 - Use AJAX for all data operations
 - Update the DOM with jQuery


## How To

 In root folder run ./mongod to start MongoDB service
 
 Uses process.env.IP instead of localhost 
 
 npm start
 
 App URL: https://expressapp2-test-ddrawer14.c9.io/
 
 JSON render route: https://expressapp2-test-ddrawer14.c9.io/users/userlist
 
 
## Flow Structure

/ (root) : 
  /routes/index.js
    /views/index.jade
      /views/layout.jade
        /public/javascripts/global.js 
          /routes/users.js
     
  