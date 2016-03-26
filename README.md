# Creating an eCommerce application

Angular makes eCommerce applications ridiculously simple to make. We can have components for each item, easy pagination/routes, and make sure all of our data is in sync with our model.

Let's create an eCommerce application.

This should have five pages - we need a home page, showing off some items that are on a special deal. It should have a products page - showing off all products and allowing the user to filter on these. We also need a cart page - this is where the user can see what they've added to their cart and go to purchase it. There should be an admin page, to allow editing of all of our data in the application. And last, we'll need the actual product view for when a user selects a product.

This will use everything we've learnt so far!

- Create our application module
- Create five pages - product list, product view, admin, cart and home page
- Have the product view have nested views - this should allow the user to swap between a list and a thumbnail view of products
- All routes should resolve the relevant data from the server
- The product page should be searchable and allow filtering from different categories
- The cart page should allow the user to remove and change quantities
- The product list should allow the user to click through to the product's full info page
- Use services to manage the cart - a user should be able to add items to their cart from any page (it should also update the cart on the backend)
- There's no need for a checkout page - the cart enough!
- Bonus: allow pagination on the product page

There should be an admin panel to add products to the system
- The products should also be removeable/editable
- Data should be validated before submission
- Categories should be able to be added/removed/edited