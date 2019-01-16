# nodePractice

This was a simple API I made when I was learning node

## Getting Started

To run the nodemon server `npm run dev`, the server will bind to localhost:8000 and you can run CRUD requests against it.

## Coded Endpoints

`/notes` is for posting a new json note
```
curl --request POST \
  --url http://localhost:8000/notes \
  --header 'content-type: application/json' \
  --data '{ "title" : "this is a title",
"body" : "Boi this is a heck'\''n body"
}'
```

## Built With

* [Node](https://nodejs.org/) - All the code
* [Express](https://expressjs.com/) - Framework used
* [nodemon](https://nodemon.io/) - Running locally


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* freeCodeCamp.org
