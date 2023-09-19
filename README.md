# User-Location

Spring Bootproject using Gradle build
Application contains:
* There will be two users(ADMIN, READER)
* READER can perform only GET operation.
* ADMIN can perform Post, Put, Read.
* User-location will have three fields Name, latitude, longitude and excluded.
* Reader can call the get_users/N (where "N" will return the nearest N users from (0,0) which are not excluded).
* Role based authentication is done here using Spring security.


READ ME:

Application Manual:
Application contain three API's:
1) create_data (Input in JSON format and ID is AutoIncremented)
2) update_data (Input in JSON format and enter name from the present record to update)
3) get_users/N (where "N" will return the nearest N users from (0,0) which are not excluded)

For admin authentications:
USERNAME: admin
PASSWORD: password

User input to CREATE data is name, latitude, longitude, excluded.
User input to UPDATE data is name(enter name from the present record to update), latitude, longitude, excluded.
