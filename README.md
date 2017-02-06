# ProductStore
Web API test

This is a test project which is created as .net C# WebAPI project. There is no database. All data is stored in variables in Azure app.

Currently there is an issue with the API. It does not return anything.

URL is http://productstore20170206043829.azurewebsites.net/API/Products for getting a list of all products, but the response is only "No HTTP resource was found that matches the request URI 'http://productstore20170206043829.azurewebsites.net/API/Products'."

This API was created for controlling Raspberry pi3 GPIO. Raspberry reads control data from Azure web api and sets GPIO on or off.

After this projects works correctly Rasp code can be developed.

Another thing to develop is simple web UI to control GPIO remotely on or off.
