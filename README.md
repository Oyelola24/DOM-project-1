# 🛒 Simple Shopping Cart

This is a basic shopping cart system built using **HTML**, **CSS**, and **JavaScript**. It allows users to adjust the quantity of products, remove products from the list, like products, and automatically update the total price.

---

## ✨ Features

- Increase and decrease product quantity
- Delete (hide) products from the cart
- Like or unlike products using a heart icon
- Automatically update the total price based on quantity and unit price

---

## 🔧 How It Works

- **Plus Button (`+`)**: Increases the quantity of a product.
- **Minus Button (`-`)**: Decreases the quantity (not below 0).
- **Delete Button (🗑)**: Hides the product and sets quantity to 0.
- **Heart Icon (❤️)**: Toggles the liked status (color changes).
- **Total Calculation**: Updates dynamically based on visible products and quantities.

---

## 🧠 Technologies Used

- HTML
- CSS
- JavaScript

---

## 💡 Notes

- Unit prices are parsed from the text (e.g., `$25`) and used to calculate the total.
- Deleted (hidden) products are ignored in the total.
- Quantities and prices are updated directly in the DOM.

---

## 📄 License

This project is for learning and demonstration purposes. Free to use and modify.

