# ExpressServerWithSimplePersistence

For this assignment, write an express app that will act as a simple data store. It should respond to GET/POST requests for a single resource of your choosing. 

1. The data coming in from a POST request should be saved to a json file in a data folder in your repository, do not commit your data folder to git. For example if a POST request is sent to "/notes" with a body of {noteBody: 'hello world'} the json data in the body should be stored in it's own json file. You can pick a naming scheme for the file but I would recommend using the number of files that you have received so far.

2. A GET request to the endpoint (for example '/notes') should return a list of names (corresponding to the file names).

3. A GET request to a specific endpoint (for example '/notes/1') should return the contents of the that particular file as JSON.
