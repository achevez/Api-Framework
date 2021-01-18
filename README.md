# Api-Framework
Test API framework playground

This is a playground API test framework built with Postman.
It contains a Postman collection and environment meant to be run in Newman.

## Prerequisites:
* NPM.
* Newman (command line Collection Runner for Postman).
* htmlextra (reporter).

## Instructions to execute:
1. Clone the repository and open a terminal.
2. Go to the project folder and to run the tests, execute: newman run Woocommerce.postman_collection.json -e woocommerceEnvironment.postman_environment.json -r htmlextra
