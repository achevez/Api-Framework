# Api-Framework
Test API framework playground

This is a playground API test framework built with Postman for the Woocommerce RestAPI that supports the testing-playground project.
It contains a Postman collection meant to be executed in Newman.

## Prerequisites:
* NPM (Node Package Manager).
* Newman (command line Collection Runner for Postman).
* testing-playground app deployed (for additional information, visit: https://github.com/antonyfuentes/testing-playground).

## Instructions to execute:
1. Clone the repository and open a terminal.
2. Go to the project folder and to run the tests, execute:
```
newman run Woocommerce.postman_collection.json --env-var url=<endpoint_url> --env-var woocommerceUsername="<username>" --env-var woocommercePassword="<password>"
```