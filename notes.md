- git status
- mkdir foldername
- git init
- npm init -y
- code .
- npm i nodemon -D <- install nodemone as a development time dependency
- npx gitignore node

endpoint(url + http method) === function

POST /api/movies (body: movie) === postApiMovies(movie)

| non REST        |          REST          |
| :-------------- | :--------------------: |
| /createdMovie   |    POST /api/movies    |
| /removeMovie:id | DELETE /api/movies/:id |

Other approaches to building web API

- GraphQL
- gRPC
- RPC
- SOAP
