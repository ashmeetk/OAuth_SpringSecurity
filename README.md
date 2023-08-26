# OAuth_SpringSecurity
A basic OAuth server is implemented with Google as authorization server

In the Google API console, we have created a new client, with scope to be specified to client with username and email and set it in application.properties.
When the user enters http://localhost:8080 in chrome, he is directed to OAuth google server where instead of providing his credentials to the app, he enters with his google credentials. Google asks user that the client app requests the username and email, so should google provide the app with them? When the user gives his permission, the client app is able to access username and email. 
