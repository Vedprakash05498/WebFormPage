# WebFormPage
"This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for creating web page form to save different operations."

![Screenshot 2022-12-06 at 9 50 54 PM](https://user-images.githubusercontent.com/47717448/205966106-024b044b-261a-43c9-b023-83eb2c634306.png)

# Benefits of using JsonPowerDB
Simplest way to retrieve data in a JSON format.
Schema-free, Simple to use, Nimble and In-Memory database.
It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
It is low level (raw) form of data and is also human readable.
It helps developers in faster coding, in-turn reduces development cost.

# IML (JPDB Index Manipulation Language) - To insert, update and delete Json data.

Http method : POST
Base url : http://api.login2explore.com:5577
End-point url : /api/iml (mentioned in command when different)
PUT : Insert single record in the database
PUT_ALL : Insert multiple record in the database
UPDATE : Update multiple records in the database or add a new column in a record
SET : Insert a new record or update an existing record based on primary key
SET_ALL : Insert and update records based on primary key
REMOVE : Remove records from the database

# Response Headers in JPDB :

One or more of the following information may be returned in the response, all of which give time in milliseconds unit. All information will be returned with IML, IRL, IDL, ISL APIs.
serverTime - Time between receiving request and returning response by JsonPowerDB Server.
reqResTime - Time taken to convert request to reponse by the API (not in the KVP API). It's the combination of parseTime and execTime.
parseTime -Time taken to parse and validate the request.
execTime - Actual time of executing the validated request.

#JPDBObject.js
Synchronized JPDBObject
-A javascript tool to synchronize the JsonPowerDB database for client, salient features are:
-Synchronized -keep the data at client localStorage in sync with the JPDB database.
-AI - intelligent enough to sync data as per individual client requirements.
-Allows to keep multiple instance of JPDBObject, each on different JsonPowerDB database.
-Easy and fast for application development.
-Seamless experience for developers to code for JsonPowerDB databases.
![Screenshot 2022-12-06 at 9 58 16 PM](https://user-images.githubusercontent.com/47717448/205967886-6457d7fd-4517-4276-bd59-2a78da53e4d3.png)
![Screenshot 2022-12-06 at 9 58 30 PM](https://user-images.githubusercontent.com/47717448/205967990-39d8c90c-324f-42c1-9d2d-c895567771cc.png)
# Alert
![Screenshot 2022-12-06 at 9 59 53 PM](https://user-images.githubusercontent.com/47717448/205968312-c2feccbb-fdee-492d-96cd-16c722f33096.png)

# Form structure
![Screenshot 2022-12-06 at 10 01 36 PM](https://user-images.githubusercontent.com/47717448/205969577-1cec4e0d-f81c-4eab-8d25-ce1d32f6eedc.png)

# Filling Data
![Screenshot 2022-12-06 at 10 03 47 PM](https://user-images.githubusercontent.com/47717448/205969843-93c68c42-944d-46fe-96b0-9d97aca1341f.png)

# Save Data
![Screenshot 2022-12-06 at 10 04 28 PM](https://user-images.githubusercontent.com/47717448/205969926-18dbc02b-ad07-4583-92c4-bcecd1dada4d.png)

# Alert Save Data address
![Screenshot 2022-12-06 at 10 04 59 PM](https://user-images.githubusercontent.com/47717448/205970419-ab665f4a-2430-4153-a99b-b4ed5ed8871d.png)






