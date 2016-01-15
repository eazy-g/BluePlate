GET/api/getDeals => gets all deals from database

POST/api/getDeals => creates a deal from req.body and sends a 201

body: {
	restaurant_id: INTEGER,
  	description: varchar(5000),
  	expiration: INTEGER (ex: 1700, 24 hr time) 
	}

POST/api/login => selects username where they match and then runs a function to check password against database. if they match it sends a 201.

body: {
	"username": "person person", 
	"password": "abc"
	}