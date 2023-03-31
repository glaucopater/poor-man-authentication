# poor-man-authentication
JavaScript only clientside authentication

Many times you are in the situation of disabling access to a specific part of your application or website.
In general this could be achieved using:
- Basic Auth (a configuration available only web server side like nginx, apache, iis etc ) 
- Custom Login form via username and password (client side and server side are involved, the password should be stored in general on a database and crypted)
- Cookie or JWT exchange (both server side and client side involved again)

The goal of this project is to provide an alternative solution that could rely only on client side JavaScript.
Caveat: this is not to replace the above points but to provide a possible alternative to segregate part or completely your application.
