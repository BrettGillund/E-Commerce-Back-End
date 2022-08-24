## E-Commerce Back End Application

# Video Walkthrough of Application



# About

This is an ecommerce application where users can connect to a database and use a number of different routes to create, view, update, and delete a number of different variables.
# Starting the Application

Starting this Social Network Applicaiton is as easy as entering a users credentials within the .env file. Then a user will need to open their terminal and use the npm i command to download the necessary packages to run the application. From there the user can run npm seed followed by npm start in the main directory of this application which will seed the database and launch the applicaiton's server. 

Finally, users can add data through the various API routes listed in the routes/api file. Please see the below table in regard to referencing these routes.

# Functionality and Routes:


USER ROUTES:

- Getting all categories.
    - To view all categories in insomnia a user will need to GET to the http://localhost:3001/api/categories route. All existing categories will populate in the preview tab.

- Getting a single category by ID.
    - To get a single category by ID in insomnia a user will need to GET to the http://localhost:3001/api/categories/:categoriesId route passing an individual category ID into the categoriId field.

- Creating a category.
    - To create a category in insomnia a user will need to POST to the http://localhost:3001/api/categories route passing in an object containing "category_name" parameter.

- Updating a users information.
    - To update a single category in insomnia a user will need to PUT to the the http://localhost:3001/api/categories/:categoriesId route passing an individual categories ID into the categoriesId field. Additionally, they will need to pass in an object including the "category_name" they would like to have updated.

- Deleting a category.
    - To delete a category in insomnia a user will need to DELETE to the http://localhost:3001/api/categories/:categoriesId route passing an individual category ID into the userId field.


- Getting all products.
    - To view all products in insomnia a user will need to GET to the http://localhost:3001/api/products route. All existing products will populate in the preview tab.

- Getting a single products by ID.
    - To get a single products by ID in insomnia a user will need to GET to the http://localhost:3001/api/products/:productsId route passing an individual users ID into the productsId field.

- Creating a product.
    - To create a product in insomnia a user will need to POST to the http://localhost:3001/api/products route passing in an object containing "product_name", "price", "stock", "category_id", and "tagIds" parameters.

- Updating a products information.
    - To update a single products  information in insomnia a user will need to PUT to the the http://localhost:3001/api/products/:productsId route passing an individual products ID into the productsId field. Additionally, they will need to pass in an object including the parameter they would like to have updated.

- Deleting a product.
    - To delete a product in insomnia a user will need to DELETE to the http://localhost:3001/api/products/:productsId route passing an individual products ID into the userId field.

- Getting all tags.
    - To view all tags in insomnia a user will need to GET to the http://localhost:3001/api/tags route. All existing tags will populate in the preview tab.

- Getting a single tag by ID.
    - To get a single products by ID in insomnia a user will need to GET to the http://localhost:3001/api/tags/:tagsId route passing an individual tagId into the productsId field.

- Creating a tag.
    - To create a product in insomnia a user will need to POST to the http://localhost:3001/api/tags route passing in an object containing the "tag_name" parameter.

- Updating a tags information.
    - To update a single tags information in insomnia a user will need to PUT to the the http://localhost:3001/api/tags/:tagsId route passing an individual tags ID into the tagsId field. Additionally, they will need to pass in an object including the parameter they would like to have updated.

- Deleting a tag.
    - To delete a tag in insomnia a user will need to DELETE to the http://localhost:3001/api/tags/:tagsId route passing an individual tags ID into the userId field.


# Technologies

- Express.js for routing
- Mysql
- Insomia for testing routes
- JavaScript as a programming language.
- Sequelize