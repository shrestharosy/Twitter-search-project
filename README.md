# Twitter search project
Must have node.js, angular.js installed

Go to twitter-search directory, <br>
```npm install```

Create an app in http://apps.twitter.com and get a consumer key and consumer secret<br>

Go to backend directory, the backend is node.js server<br>
```npm install express request body-parser cors --save--dev```

In backend>config.js<br><br>
Provide consumerkey and consumersecret obtained from above
 	```consumerkey: '<consumerkey here>',
  consumersecret:'<consumersecret here>',  ```

Go to backend directory, start server<br>
```node server.js```

Go to twitter-search directory, start frontend<br>
```ng serve --open```
Navigate to `http://localhost:4200/`<br>
