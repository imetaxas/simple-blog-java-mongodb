The code implements a very simple blog application using Java8, Spark, Freemarker and MongoDB.

Setup
------

1. Start a mongodb server instance:
   mongod

2. Import the posts.json file in mongodb:
   mongoimport --db <db name> --collection <collection name> --file <file location>

   E.g: mongoimport --db blog --collection posts --file c:\data\posts.json

3. Run the BlogController:
   java BlogController

4. Open the URL http://localhost:8082

Pages
------
1. Go to Blog Home     -   http://localhost:8082
2. Signup              -   http://localhost:8082/signup
3. Login               -   http://localhost:8082/login
4. Logout              -   http://localhost:8082/logout
5. Create New Post     -   http://localhost:8082/newpost

Operations
-----------
1. Open a post
2. Add a comment
3. Like a comment
