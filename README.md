# React Pizza Parlor

Group project for Ty, Sam, Steve, and Atticus.

Assign out tasks and use branches to allow team members to work in parallel.

Start with your `/api/pizza` GET route to give client side developers something to work with.

### Setup

Create your database and tables using the provided `data.sql` file. Start the server.

```
npm install
npm run server
```

Now that the server is running, open a new terminal tab with `cmd + t` and start the react client app.

```
npm run client
```

## MVP REQUIREMENTS

Build a pizza ordering system. A list of pizzas currently offered is in SQL format (`data.sql`).

Build out the following views:

### MENU

Display all of the pizzas on the screen. Allow users to increase or decrease the quantity of each pizza they would like to order. Show the total cost of items in the cart in the top right of this page.

### CHECKOUT

Include an input field for the users name and display a table of pizzas they have added to the cart. Users should not be able to modify item totals on this screen. When they click checkout, the users *name* and *order total* should be sent to the server and saved in the database.

### ORDERS

This page **should not** appear in the navigation bar. Eventually the client would like to add authentication but for now, it will be available to anyone with the url [http://localhost:3000/orders](http://localhost:3000/orders). This page will display the name, time and order total for each of the orders placed.

## STRETCH GOALS

- Create a new route that allows admins to add pizzas [http://localhost:3000/admin](http://localhost:3000/admin).
- Improve the stying of the app using Material-UI cards, buttons, nav bar and icons.
- Create a junction table and keep track of which pizzas are added to each order.
- Display a list of pizzas for each order on the orders page. 
- Add a button on the orders page to track delivery status.
- Give each pizza an image url and add pictures to the `public/images` folder.
