Two sets of API will be available in the request.rest

The second API (POST http://localhost:3000/login) will provide the token based on username in body, and with that token generated you can call the second api(GET http://localhost:3000/posts) which would give the correspoding object which would expire after 40s.
