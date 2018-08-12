## TODO API

A demo project to show how consise Rest API's can be built in golang.

This is to disperse the myth that api's written in golang cannot be simple and idiomatic like in other programming languages.

Each folder in this repository represents different stages in an api project's life cycle:
- basestructure/ : Shows to structure your rest project into mudular bits with expressive routing, handlers and middlewares. Subsequent projects in the folder will build on top of basestructure.
- withmongodb/ : Shows how to handle application configuration using viper, and how make a mongodb connection, and pass it alongside the configuration using struct compositions and methods. 
- withmgonclosures/ : Shows how to pass around application configuration or other shared data around the application using closures, and some of the problems that can arise from using closures. 


