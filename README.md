# bearer_authorization

Author: Alistair Blake
## Learning Objectives:
This code implements a Bearer Authentication system with a token expiry (15 minutes), api keys, and single use token.


Altered the JWT to be time sensitive (valid for 15 minutes)
Altered the JWT to be single-use:
with every authenticated access,
re-sent a new JWT token as a cookie/ header
•	middleware.js - Handled the Bearer Header to pull and verify with the token
•	users-model.js - Added a bearer authorization method that verifies the token
•	Will Create a few users+passwords to test with

•	Added support for the creation and usage of time sensitive (valid for 15 minutes) JWTs

### Links and Resources:
[Repo](https://github.com/Alwynblake/bearer_authorization )

### In order to run:
* start server: `nodemon`
* start mongo db: `mongod --dbpath ./db`