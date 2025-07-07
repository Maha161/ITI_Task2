# 🍕 Black Goose Bistro | Pizza Ordering Form

A pure HTML pizza ordering form for Black Goose Bistro that allows customers to customize and order pizzas online.

---

## 🍕 Project Overview

This HTML application provides a complete pizza ordering interface where customers can:

- Submit their personal and delivery information.
- Customize pizza with various crust and topping options.
- Specify the quantity of pizzas needed.
- Submit or reset their order.

---

## ✨ Features

### 🧾 Customer Information

- Name, address, phone, and email fields.
- Delivery instructions (optional, up to 400 characters).

### 🍕 Pizza Customization

**Crust types**:

- Classic White , Multigrain , Stuffed Crust , Gluten-free.

**Toppings**:

- Red Sauce , White Sauce , Mozzarella , Pepperoni , Mushrooms , Peppers , Anchovies

**Quantity**:

- Input field with numeric validation.

---

## 🛠️ Technology Used

- Pure **HTML5**.
- Semantic HTML elements.

---

## 💡 Meta Tags Used

```html
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="author" content="Maha Ebrahim" />
<meta
  name="description"
  content="Order your custom pizza from Black Goose Bistro. Choose crust and toppings with your own delivery instructions."
/>
<meta
  name="keywords"
  content="pizza, crust, order form, restaurant, custom pizza, Black Goose Bistro"
/>
```

## 🚀 Getting Started

### ✅ Requirements

- Any modern browser (Chrome, Firefox, Edge, Safari).
- A text editor like **VS Code** (if you want to edit the file).

---

### ▶️ How to Run

- Save the HTML file as `index.html`.
- Double-click the file to open it in your browser.

---

## 📋 Usage Guide

### 📝 Placing an Order

- Enter your information in the "Your Information" section.
- Customize your pizza:
  - Select one crust type.
  - Choose as many toppings as desired.
  - Specify the quantity.
- Submit your order using the **"Bring me a pizza!"** button.
- Use the **"Reset"** button to clear all selections.

---

### ✅ Validation

- Email must follow a valid format.
- Quantity must be numeric (validated using `inputmode="numeric"` and `pattern`).
- Delivery instructions can contain up to 400 characters.

---

## 🔧 Project Structure

```
index.html
├── <head>     # Document metadata (title, meta tags)
├── <body>
│   ├── <header>   # Page header with navigation
│   ├── <main>
│   │   └── <form> # Pizza order form
│   │       ├── Customer info section
│   │       └── Pizza customization section
```

---

## 🤝 How to Extend

To make this project production-ready, you could:

- Add CSS for styling and responsiveness.
- Add JavaScript for dynamic validation or interactivity.
- Add a backend to store order data.
- Set a `form` action to send data to a server.

---

## 📞 Contact

For questions about this HTML implementation, please contact:  
**Maha Ebrahim** (meta author).
