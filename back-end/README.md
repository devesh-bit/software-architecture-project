## Software Architecture Project Back End

### To run this project, do the following:

##### create .env with the following code (update credentials). Make sure to create .env in the root directory of the project. nodeapi/.env

```
APP_NAME=nodeapi
MONGO_URI=mongodb://localhost:27017/api
PORT=8080
JWT_SECRET=xxxxxx
CLIENT_URL=http://localhost:3000
REACT_APP_GOOGLE_CLIENT_ID=xxxxxx.apps.googleusercontent.com
```

For mongoDB you can either run the mongoDB cluster locally or use mlab, I found this blog post helpful to set it up. https://medium.com/@umarmagaji/connecting-mongodb-using-mlab-with-node-js-application-fd3de5b94a7a 

### Setup locally.

1. Fork the repository.
2. Clone the repository.
3. Navigate into cloned repository.

    ``` cd nodeapi ```

4. Open terminal execute following commands.

    ``` npm install && npm run dev ```

5. Navigate to http://localhost:8000
