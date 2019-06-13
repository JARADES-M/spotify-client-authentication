# Simple Cient App Authentication API

### How to Use
Set up you ambient variables with the **CLIENT_ID** and **CLIENT_SECRET**.
that you can get by creating an app on [Spotify for Developers](https://developer.spotify.com/dashboard/applications/)
#### Linux
> export CLIENT_ID=<YOUR CLIENT_ID> ...
#### Windows
> export CLIENT_ID=<YOUR CLIENT_ID> ...


Rum the application:
```sh
npm install
node app.js
```
From your browser or HTTP Client you can use the following `url` to get the _Token_
[`http://localhost:8888/spotify/auth`](http://localhost:8888/spotify/auth)
```JavaScript
 "{"token": "...xdqg8oVXTLvAu0gU1ViuTmHVy02GI..."}"
```



- [Jarades Monteiro](https://www.linkedin.com/in/jarades)