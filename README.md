# Multiple-API-Data-Fetch

This website has a button that, when clicked, initiates a promise chain consisting of three functions, each of which returns a promise with a different delay using setTimeout().
 
Inside each setTimeout() call, data is fetched from three different APIs and displayed on the screen in a suitable UI. Once the data is displayed, the promise is resolved by calling resolve (true). The next promise in the chain will be executed only if the previous promise is resolved successfully.
 
Overall, the goal of this web application is to show how to use promises and the fetch API to chain multiple API requests together, as well as how to display the fetched data on the screen in an appropriate UI.
