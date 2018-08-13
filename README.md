# :octocat: ITEM_CATALOG :volcano::partly_sunny:
a full website:milky_way: with JSON API using Oauth2 provider for authentication with authorized users:rocket:.

## Used Technology:hammer:
* FLASK Framework:statue_of_liberty:
* Oauth2 provider:rainbow:
* SQLAlchemy:airplane:
# SETUP :fuelpump:
* first:pushpin: you need to download this project using the command: 
```
git clone https://github.com/hazemkhaledmohamed/ITEM_CATALOG 
```
* then run **Database_Setup.py** to initialize the database with null values with name **ItemsCatalogWithUsers.db**:umbrella:
* after that you need to write some data to the Data-Base file to test this app so run **Fake_Items.py**:ring:
* then run **APP.py**:full_moon: to run the server with home address **https://localhost:5000** with port 5000

# files contained in the project:seedling:
* ##**APP.py**:full_moon: this file contains tha whole app along with initializing the server 
* **Fake_Items.py**:waning_gibbous_moon: this file initialize the database with some data to load to the server
* **Database_Setup.py**:last_quarter_moon: this file has the properties of serializing data to JSON format to be loaded to API endpoing 
* **ca.crt**:waning_crescent_moon: certificate file to install Https with the server 
* **ca.key**:new_moon: key file for certificate installation 
* **client_secrets.json**:earth_asia: Json file for google authentication with users in order to get token for each user while the server is running 
* **fb_client_secrets.json**:milky_way: Json file for google authentication 

#file
