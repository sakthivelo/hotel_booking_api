# hotel_room_booking_api
It contains api for hotel room booking

steps to install:
------------------
1) clone the repo
2) use command "npm install"
3) start api using the command "npm start"

steps for DB:
-------------
1) install MongoDB server in your machine

DB:
---
hotelbooking

Collections
------------
hotels
roombooking

hotel - data
[{
  "_id": {
    "$oid": "677e37f83ce091adcad4b053"
  },
  "name": "Hotel 1",
  "location": "Chennai",
  "rooms": 100,
  "availableRooms": 50,
  "hotelId": "hotel1"
},
{
  "_id": {
    "$oid": "677e380c3ce091adcad4b055"
  },
  "name": "Hotel 2",
  "location": "Coimbatore",
  "rooms": 100,
  "availableRooms": 50,
  "hotelId": "hotel2"
},
{
  "_id": {
    "$oid": "677e381a3ce091adcad4b057"
  },
  "name": "Hotel Sunshine",
  "location": "Hyderabad",
  "rooms": 100,
  "availableRooms": 49,
  "hotelId": "hotel3"
},
{
  "_id": {
    "$oid": "677e38283ce091adcad4b059"
  },
  "name": "Hotel Sunshine",
  "location": "Bangalore",
  "rooms": 100,
  "availableRooms": 39,
  "hotelId": "hotel1"
}]
