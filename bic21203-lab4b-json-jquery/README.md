# Lab 4b – Client-Side Scripting (JSON and jQuery)

**Name:** Yasmin Nadhirah binti Zainal  
**Student ID:** AI240084  
**Course:** BIC21203 Web Development  
**University:** Universiti Tun Hussein Onn Malaysia (UTHM)

## 1. Introduction

This lab focuses on using JSON, JavaScript, and jQuery in web development. The activities involve creating JSON data, retrieving and displaying information using JavaScript, and manipulating HTML elements using jQuery.

## 2. Question 1 – Create and Structure JSON Data

**Description:**

This task involves creating a JSON file named `books.json` containing information about two books.

**How It Works:**

- The JSON file contains a `books` array.
- Each book has a title, author, publication year, and genres.
- The data is stored using JSON objects and arrays.
- The JSON structure uses double quotation marks and correct data types.

**Book Information:**

| Property | Book 1 | Book 2 |
|---|---|---|
| Title | The Great Gatsby | To Kill a Mockingbird |
| Author | F. Scott Fitzgerald | Harper Lee |
| Publication Year | 1925 | 1960 |
| Genres | Fiction, Classics | Fiction, Coming-of-Age |

## 3. Question 2 – Retrieve and Display JSON Data

**Description:**

This webpage retrieves information from `books.json` using JavaScript `fetch()` and displays selected book details.

**How It Works:**

- The `fetch()` function retrieves data from `books.json`.
- The JSON response is converted into a JavaScript object using `response.json()`.
- JavaScript accesses the required book information.
- The results are displayed on the webpage using `textContent`.
- An error message is displayed if the JSON file cannot be loaded or parsed.

**Expected Output:**

First Book: The Great Gatsby

Second Book Author: Harper Lee

The Great Gatsby - Fiction, Classics

To Kill a Mockingbird - Fiction, Coming-of-Age

## 4. Question 3 – Compare Native JavaScript and jQuery

**Description:**

This task demonstrates how jQuery can be used to modify HTML elements and handle button events.

**How It Works:**

- `.text()` changes "Original Text" to "Modified Text".
- `.addClass()` adds the `myStyle` class to a div element.
- `.on("click")` displays an alert when the button is clicked.

**Expected Output:**

- The webpage displays "Modified Text".
- The div element has a coral background.
- Clicking the button displays "Button clicked!".

### Native JavaScript vs jQuery

**Native JavaScript:**

Native JavaScript does