# Sentences_DB_API

Implemented a REST API for a database that stores and retrieves sentences on basis of token. Each user is given 10 tokens initially. Once tokens are exhausted, they cannot further query their request.

Technologies used - Python Flask, Flask_Restful, Bcrypt, MongoDB, Docker

The below diagram represents the functionalities implemented

![Sentences_DB_API](https://user-images.githubusercontent.com/112655255/194703629-097f104c-3029-4184-923d-d8d20d3f75a3.jpg)

In end, Docker was used to generate an image on the given configuration and was run using container.
