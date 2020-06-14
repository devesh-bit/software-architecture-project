# software-architecture-project
Back End & Front End have their respective readme files with instructions to run the project.


### REST API
* Uses HTTP verbs POST, GET, PUT, PATCH, and DELETE to perform CRUD Operations.
* Implements Hypermedia Control e.g - https://github.com/devesh-bit/software-architecture-project/blob/master/back-end/routes/post.js#L42
* API is safe.
* API supports pagination & filters.

### DB
* For database I have relied on MongoDB, and mongoose as an ORM.
* Implements some commanly used patterns in Non-Relational Database.

### JWT 
* Manual Implementation of authentication is implmented using JWT web token. I have use NPM package to perform operations on   token https://www.npmjs.com/package/jsonwebtoken
* User can login from front-end.
* Currently application supports Google auth as third party auth. for which npm package https://www.npmjs.com/package/google-auth-library is being used.
* User reg. working from front-end.
* Users have different role as mentioned in schema https://github.com/devesh-bit/software-architecture-project/blob/master/back-end/models/user.js#L42
* users can edit settings from front-end.

### FrontEnd
* MVC architecture is being followed, React acts as View layer, controllers & models are in back-end.
* Front end routing using `react-router-dom`
* Reactive web app with no SSR.
* Application uses Material Desighn mobile responsive framework.
* Bundled using CRA.

### DevOps
* Travis pipeline is implemented, config can be found in `.travis.yml`
* I haven't written unit tests for client/server.
* Docker instructions are written in `Dockerfile` in back-end.

