# Redux Cart

A React application that demonstrates building a shopping cart using Redux Toolkit for state management.

## Features

- Browse and add products to the cart
- View cart items with quantities and totals
- Persist cart data across sessions
- Display notifications for cart actions (add, remove, etc.)
- Responsive UI with modular CSS

## Technologies Used

- **React**: Frontend library for building the user interface
- **Redux Toolkit**: For efficient state management
- **React Redux**: Integration of Redux with React
- **Create React App**: Build setup and development server

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd redux-cart
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

The app will be available at `http://localhost:3000`.

## Usage

- Browse the list of products on the main page.
- Click "Add to Cart" on any product to add it to your cart.
- Click the cart button in the header to view your cart items.
- In the cart, you can increase/decrease quantities or remove items.
- Cart data is automatically saved and loaded on app start.

## Available Scripts

- `npm start`: Runs the app in development mode.
- `npm build`: Builds the app for production to the `build` folder.
- `npm test`: Launches the test runner in interactive watch mode.
- `npm eject`: Ejects from Create React App (irreversible).

## Project Structure

```
src/
├── components/
│   ├── Cart/
│   │   ├── Cart.js
│   │   ├── CartButton.js
│   │   ├── CartItem.js
│   │   └── Cart.module.css
│   ├── Layout/
│   │   ├── Layout.js
│   │   ├── MainHeader.js
│   │   └── MainHeader.module.css
│   ├── Shop/
│   │   ├── Products.js
│   │   ├── ProductItem.js
│   │   └── Products.module.css
│   └── UI/
│       ├── Card.js
│       ├── Card.module.css
│       ├── Notification.js
│       └── Notification.module.css
├── store/
│   ├── index.js
│   ├── cart-slice.js
│   ├── cart-actions.js
│   └── ui-slice.js
├── App.js
├── index.js
└── index.css
```

## Contributing

Feel free to submit issues or pull requests for improvements.

## License

This project is for educational purposes.
