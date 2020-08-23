# creating-node.js-server
creating node.js server

// first we import the 'http' module using 'require()' function

// then we use the 'createServer()' function of the 'http' module which takes a function as a argument (parameter) and this function takes two default parameters passed by node.js that are 'request' and 'response'

// then we could write any code inside the function which we wnat to execute and it would return a server in a vairiable

// But to make the server listen the request we need to activate it for listening that is basicaly to start a EVENT LOOP, so for this we use 'listen()' function and also pass the port number in it

// after this we first need to start executing the file using the terminal using command

// node app.js

// we will see that our execution wont finish it will keep running

// In the mean while if we excess localhost:3000 our code will execute and we will see the result in the terminal i.e in this case is the 'request' parameter will be printed
