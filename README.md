# ORM Database

Using Object-Relationship Mapping (ORM) this app shows the backend of an ecommerce site, by running our seed files, we can fill our data base with products, and the product tags and categories, visually accessable trough insomnia

## Installation

First make sure that insomnia is downloaded and up to date, then in the integrated terminal of the develop folder run npm i. After doing so, seed your database by entering into mysql (in the terminal run mysql -uroot -p(whatever your password is)), then run source db/schema.sql, then run quit.

## Usage

After that run npm seed, and then npm start. You can then access the database through insomnia, by entering localhost:3001, and then the get routes provided below. 

localhost:3001/api/products, to see our products.

localhost:3001/api/categories, to see the products in their respective categories.

localhost:3001/api/tags to see the products under their respective tags.

You can then use the post, put, and delete routes to add, update, and delete products, categories, and tags.

## Test

To test it, simply install the app, open insomnia and follow the routes provided above.

## Contributing/Contact

To submit bug reports, feature requests, or pull requests, please email me at hannibr26@gmail.com, or visit my GitHub page: brockhanni(https://github.com/brockhanni)

## Deployment

GITHUB

## Screenshots

Check out the video walkthrough below!

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Test](#test)
- [Contributing/Contact](#contributing/Contact)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Table of Contents](#table-of-contents)
