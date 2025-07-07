# 🍕 Black Goose Bistro | Pizza Ordering Form

A pure HTML pizza ordering form for Black Goose Bistro that allows customers to customize and order pizzas online.

## 🍕 Project Overview

This HTML application provides a complete pizza ordering interface where customers can:
.Submit their personal and delivery information
.Customize pizza with various crust and topping options
.Specify the quantity of pizzas needed
.Submit or reset their order

## ✨ Features

### 🧾 Customer Information

.Name, address, phone, and email fields
.Delivery instructions (optional, up to 400 characters)

### 🍕 Pizza Customization

-**Crust types** (choose one):

.Classic White
.Multigrain
.Stuffed Crust
.Gluten-free

-**Toppings** (choose multiple):

    .Red Sauce, White Sauce, Mozzarella, Pepperoni, Mushrooms, Peppers, Anchovies

-**Quantity** input with numeric validation

## 🛠️ Technology Used

-✅ Pure **HTML5**
-✅ Semantic structure using:

- <form>, <fieldset>, <legend>, <label>,   <input>,    <textarea>
  -❌ No CSS, JavaScript, or backend logic

## 🚀 Getting Started

### ✅ Requirements

.Any modern browser (Chrome, Firefox, Edge, Safari)
.Text editor (e.g., VS Code) if editing

### ▶️ How to Run

1.Save the HTML file as 'index.html'
2.Double-click to open in browser

## 📋 Usage Guide

📝 Placing an Order
1- Enter your information in the "Your Information" section
2-Customize your pizza:
.Select one crust type
.Choose as many toppings as desired
.Specify quantity
3-Submit your order with the "Bring me a pizza!" button
4-Use the "Reset" button to clear all selections

✅ Validation
.Email must follow a valid format
.Quantity must be numeric (validated via inputmode="numeric" and pattern)
.Delivery instructions can contain up to 400 characters

## 📋 HTML Elements Used

📄 Document Structure
1-<!DOCTYPE html> – Declares the document as HTML5
2-<html> – Root element of the HTML page
3-<head> – Contains metadata (not visible to users)
4-<meta> – Defines character set, author, keywords, and description
5-<title> – Sets the browser tab title

🧱 Page Layout
1-<body> – Contains all visible content
2-<header> – Top section with navigation and heading
3-<nav> – Navigation menu
4-<ul> / <li> – Unordered list of nav links
5-<a> – Anchor/link element
6-<main> – Primary content area
7-<section> – Groups related content areas
8-<div> – Generic container for layout or grouping

📝 Form Elements
1-<form> – Wraps the entire order form
2-<fieldset> – Groups form fields logically
3-<legend> – Labels for fieldsets
4-<label> – Descriptive text for input elements
5-<input> – Form controls:
type="text" – Name, address
type="email" – Email input
type="tel" – Phone number
type="radio" – Choose one crust option
type="checkbox" – Choose multiple toppings
type="submit" and type="reset" – Buttons
6-<textarea> – For delivery instructions (multiline input)

📋 Tables (Used for layout in the contact section)
1-<table> – Container for tabular layout

  <tr> – Table row
  <td> – Table cell

📐 Other Elements
<sup> – Superscript
<br> – Line breaks for spacing

## 🔧 Project Structure

index.html
├── <head> # Document metadata(title, meta tags)
├── <body>
│ ├── <header> # Page header with navigation
│ ├── <main>
│ │ └── <form> # Order form
│ │ ├── Customer info section
│ │ └── Pizza customization section

## 🤝 How to Extend

To make this production-ready, you would need to:
. Add CSS for styling and responsiveness
. Add JavaScript for dynamic validation or interactivity
. Add a backend to store orders
. Set a form action to send data to a server

## 📞 Contact

For questions about this HTML implementation, please contact:
Maha Ebrahim (meta author)
