# first-rest-api

A REST API showing the demo of a simple store.

## Endpoints

- POST/ store data {name} - Creates a new store with a given name.
- GET/ store/ <string:name> - To return data about the given store name.
- GET/ store - Return a list of all the stores.
- POST/ store/ <string:name> /item - Create an item inside a specific store with a given name.
- GET/ store /<string:name> /item - Gets all the iems in a specific store.