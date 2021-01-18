# 🛍️-Shop-Shop

  ![GitHub](https://img.shields.io/github/license/kpehl/shop-shop?style=plastic)
  
  ![Most recent commit](https://img.shields.io/github/last-commit/kpehl/shop-shop)
  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kpehl/shop-shop)

## Project Description
This project refactors a fictional e-commerce application to use Redux-esque global state control using React libraries. Stripe is used for payments.  

## Installation
If you would like to modify the code, clone the project onto your computer, and run `npm install` in the root directory, in the client directory, and in the server directory.

From the root directory, type `npm start` to start the Express and GraphQL/Apollo servers. The homepage of the application will open in your default browser.

## Usage
The application is deployed at: https://damp-brushlands-27685.herokuapp.com/

You can log in as 
`fake@email.com`
`test12345`

You can then see order history and test the shopping function. When you check out, you will be directed to a test mode Stripe storefront.

For testing purposes, `4242 4242 4242 4242` can be used as the credit card number with any future date for the expiration date and any three digits for the CVC.

## Screenshot
![screenshot](shop-shop-screenshot.png)
