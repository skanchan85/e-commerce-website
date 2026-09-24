# ShopSphere – E-Commerce Web Application

ShopSphere is a responsive front-end e-commerce web application developed using **HTML5, CSS3, JavaScript and Bootstrap 5**.

## Features

- Responsive Bootstrap navigation bar
- Home page with featured products
- Product listing with images
- Product search
- Category filtering
- Product details page
- Add to Cart
- Increase/decrease cart quantity
- Remove items from cart
- Automatic subtotal, delivery and total calculation
- Demo checkout form
- Cart persistence using `localStorage`
- Contact / Help Center
- FAQ accordion
- Mobile, tablet and desktop responsive design

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Bootstrap 5
- Browser LocalStorage
- SVG images

## Project Structure

```text
ShopSphere_Ecommerce/
│
├── index.html
├── products.html
├── product-details.html
├── cart.html
├── contact.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   ├── app.js
│   └── products-data.js
│
└── images/
    ├── hero.svg
    ├── headphones.svg
    ├── watch.svg
    ├── shoes.svg
    ├── backpack.svg
    ├── lamp.svg
    └── mug.svg
```

## Pages

### Home — `index.html`
Includes the hero section, featured products, navigation, shopping CTA and feature highlights.

### Products — `products.html`
Includes product cards, images, prices, ratings, descriptions, search, category filters, Add to Cart and Details buttons.

### Product Details — `product-details.html`
Displays the selected product's image, name, category, rating, price, description and specifications.

### Cart & Checkout — `cart.html`
Provides cart management, quantity controls, item removal, subtotal, delivery charge, total and a demo checkout form.

### Contact / Help — `contact.html`
Includes a contact form and FAQ/help center using Bootstrap accordion components.

## Cart Functionality

Cart data is stored in the browser using `localStorage`, so products remain in the cart after a page refresh.

Example:

```javascript
[
  { "id": 1, "qty": 2 },
  { "id": 3, "qty": 1 }
]
```

## Checkout

The project contains a **demo checkout flow** with:

- Full name
- Email
- Delivery address
- Payment method
- Place Order action

> This is a front-end portfolio project. It does not process real payments or create real orders.

## Search & Filtering

Products can be searched by name or description and filtered by:

- Electronics
- Fashion
- Home

## Responsive Design

The website is designed for:

- Mobile phones
- Tablets
- Laptops
- Desktop screens

Bootstrap's responsive grid and navbar are combined with custom CSS media queries.

##  How to Run

### Using VS Code

1. Download and extract the project.
2. Open the folder in Visual Studio Code.
3. Install the **Live Server** extension.
4. Right-click `index.html`.
5. Select **Open with Live Server**.
6. The website will open in your browser.

You can also open `index.html` directly in a modern browser.

## Mobile Testing

You can test the project on Android using an HTML/code editor with preview support, such as Acode.

1. Download the ZIP.
2. Extract it.
3. Open the project folder in the editor.
4. Open `index.html`.
5. Start the HTML preview.

## Testing Checklist

- [ ] Home page loads
- [ ] Responsive navbar works
- [ ] Products display correctly
- [ ] Search works
- [ ] Category filters work
- [ ] Product details work
- [ ] Add to Cart works
- [ ] Cart count updates
- [ ] Quantity controls work
- [ ] Remove item works
- [ ] Subtotal and total update
- [ ] Checkout modal opens
- [ ] Demo order submission works
- [ ] Cart clears after demo checkout
- [ ] Contact form works
- [ ] FAQ accordion works
- [ ] Mobile layout works

## Project Objective

The objective of ShopSphere is to demonstrate practical front-end development skills by creating a complete e-commerce interface with dynamic product rendering, client-side cart management, responsive UI and an interactive checkout flow.

## Limitations

This is a front-end demonstration project and currently does not include:

- Backend server
- Database
- User authentication
- Real payment gateway
- Real order management
- Admin dashboard
- Inventory management
- Real shipping integration

Possible backend technologies for future development include:

```text
Java / Spring Boot
MySQL
REST API
JWT Authentication
Razorpay / Stripe
```

## Future Enhancements

- User registration and login
- Spring Boot REST API
- MySQL database
- Admin dashboard
- Real payment integration
- Order history
- Wishlist
- Product reviews
- Inventory management
- User profile
- Email order confirmation
- JWT authentication
- Cloud deployment

## Author

**Kanchan Suresh Salunkhe**  
B.Sc. Computer Application

## License

This project is created for learning, portfolio and demonstration purposes.
