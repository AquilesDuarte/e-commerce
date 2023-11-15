# E-Commerce Website

This is a simple example of an e-commerce website implemented in HTML and JavaScript. The website displays a list of products, allowing users to add items to their cart.

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
