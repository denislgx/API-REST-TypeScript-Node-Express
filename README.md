API REST made with TypeScript, Node.js and Express.

In order to test the CRUD operations follow the next steps:

1) Download or clone the repository.
2) Run 'npm install' in the root directory.
3) Run 'tsc -w' in the root directory to compile TypeScript into JavaScript. A dist folder will be created with the files inside of it.
4) Run 'npm start' to run the server.
5) Use Postman (or alike) to test the routes at 'localhost:3000/todos'. There is a POST, GET, PATCH and DELETE route. The body should be in JSON format, e.g:

{
	"id": "1", // string created randomly
	"text": "Go to the grocery store" // string
}

Note: the PATCH and DELETE routes need the id passed dynamically ('localhost:3000/todos/id').
