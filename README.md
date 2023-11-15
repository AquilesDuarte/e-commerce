# E-Commerce Website

This is a simple example of an e-commerce website implemented in HTML and JavaScript. The website displays a list of products, allowing users to add items to their cart.

## Project Structure

- **index.html**: The main HTML file that contains the page structure.
- **style.css**: A CSS file (not included here) can be added to style the page.
- **script.js**: The JavaScript file that controls the logic of displaying products and interacting with the cart.

## Features

### Product List

Products are defined in the `items` array in the `script.js` file, each with an id, name, image, and initial quantity.

```javascript
const items = [
    {
        id: 0,
        name: 't-shirt',
        img: 'image.jpg',
        quantity: 0
    },
    // ... other products ...
];
