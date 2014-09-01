In the CustomerManager directory execute 'npm install' to install Express, MongoDB and Mongoose (package.json).

Load sample data into MongoDB by performing the following steps:
* Execute 'mongod' to start the MongoDB daemon
* Navigate to the CustomerManager directory (the one that has initMongoCustData.js in it) then execute 'mongo' to start the MongoDB shell
* Enter the following in the mongo shell to load the seed files:
 * use custmgr
 * load("initMongoCustData.js")
 * load("initMongoSettingsData.js")
 * load("initMongoStateData.js")

 In the CustomerManager directory execute 'npm install' to start app

 In browser navigate to url:http://localhost:3000
 
 reference:https://github.com/DanWahlin/CustomerManager
