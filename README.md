# project_shortcuts

The below summary is a list of my past and present projects

## nc-news-frontend

**hosted:** https://ph-nc-news-frontend-project.netlify.app/  
**github repo:** https://github.com/PeteHai/nc_news  
**tech stack:** react, JS  
**description:** a web based reddit inspired forum, using the backend API previously created (see "nc-news-backend" below)  
**notes:** Now hosted, the user can complete several user journeys.  Start by logging in as the default user (not being logged in will cause the user to be unable to perform actions such as post and delete comments).  The user can sort articles by different properties and categories, view comments, post comments and vote on articles and comments (note that you cannot vote more than once!)  
**next steps:** Current styling is functional only - styling to be improved.  I also want to alter the add vote / undo vote to be an upvote/downvote but this is not critical.  Update readMe.

##nc-news-backend

**hosted:** https://pete-nc-news-project.herokuapp.com/api/  
**github repo:** https://github.com/PeteHai/nc_news_public  
**tech stack:**  PSQL, node-postgress, JS  
**description:**  This is a backend project that builds a reddit inspired news-forum api for the purpose of accessing application data programmatically.  
**notes:**   Instructions in the ReadMe.  The user can access different endpoints and make GET/POST/DELETE requests
**next steps:** add / delete / edit user endpoints to allow for more integration with the frontend
