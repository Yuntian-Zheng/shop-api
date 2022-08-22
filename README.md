# Ecommerce website
A website that allows you browse and shop for items.
# Models
- User
  - username
  - password
  - cart


- items
  - name
  - description
  - price
  - quantity
  - owner

- reviews
  - description
  - rating
  - owner
# Techology
 - MongoDB-database
 - Express-backen framework
 - Nodejs-javascript runtime
# ERD
![image](https://user-images.githubusercontent.com/48740174/186016623-dffcd3de-eb62-45d9-8ad9-cd46108cb011.png)

A user can have multiple items, and a user can have multiple reviews
# Routes
## User route

Verb | Route | Description
-----| ------ |  ------   |
POST| /sign-up | create a new account|
GET| /sign-in | sign in into account
DELETE| /signout | sign out of curent account
PATCH| /change-password |  change account password

## item route

Verb | Route | Description
-----| ------ |  ------   |
POST| /create-item| create a new item for sale
GET| /show-all-item | show all available item on home page
GET | /show-all-item/:id | show a specific item
DELETE| /delete/:id | delete specific item
PATCH| /update/:id |  update a sale item

##review

Verb | Route | Description
-----| ------ |  ------   |
POST| /review | create a new review
GET| /show-review | show all review
DELETE| /review/:id | delete a review
PATCH| /review/:id |  update a review

# link to API
https://github.com/Yuntian-Zheng/shop-client
