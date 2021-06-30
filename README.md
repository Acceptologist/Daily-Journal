# Daily-Journal

Daily Journal is a simple blogging  Node.js website app to add daily posts and store it in DataBase.


## hosted version

This app is hosted by Heroku :   https://shrouded-brushlands-89845.herokuapp.com/

## Installation & Start


Install dependencies with :

```sh
npm install
```

Launch the application with :



```sh
node app.js
```

## Usage 
The app uses Cloud database (MongoDB) to store  posts.

## API endpoints:

### /

Path | Method | Description
---|---|---
/ | GET | Get Home page 



### /about

Path | Method | Description
---|---|---
/about | GET |Get  About page 


### /contact

Path | Method | Description
---|---|---
/contact | GET |Get Contact page 


### /posts/:postId

Path | Method | Description
---|---|---
/posts/:postId | GET | Get page of the post with id=postId  

### /compose

Path | Method | Description
---|---|---
/compose | GET |Get compose page ( the page that responsible to add post) 

### /compose

Path | Method | Description
---|---|---
/compose | POST | send data that will be stored in the Cloud database 


