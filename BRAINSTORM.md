# Overview
The goal of this project is to delivery a set of apis with cors all documented with swagger.io and an UI for users to find, insert, review, rate and propose changes to restrooms all around the world.

	
# Backend

### Database

- MySQL (most likely)
- Mongo

### REST APIs

- Languages
	- Node (most likely)
	- Java
	- Python
	- Ruby 
	- PHP
	
- Localization 
	- English
	- Portugues	
	
- Endpoints
	- /restroom
	- /banheiro
	
- Models
	- Restroom
```
{
	'locationName' : 'McDonalds',
	'hashTag' : 'salvaVida',
	'address' : '111 address St',
	'city' : 'San Francisco',
	'country' : 'USA'
	'zipcode' : 94100,
	'geoLocation' : [3214132,41341241],
	'hours' : [
		[openTime, closeTime], 
		[1000, 2200],
		[1000, 2200],
		[1000, 2200],
		[1000, 2200],
		[1000, 2200],
		[1000, 2200],
	],
	'isPublic' : true,
	'isCustomerOnly' : false,
	'isHadicapAccessible' : boolean,
	'hasBabyChangingTable' : boolean,
	'createdBy' : user,
	'createdDate' : date,
	'lastModified' : date,
	'photos' : [img1, img2],
	'ratings' : [5, 0, 1, 4, 4, 4]
	'reviews' : [rev1, rev2],	
}
```


# Frontend

- Framework
	- Angular
	- Backbone
	- React
