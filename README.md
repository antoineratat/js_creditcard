# JS Credit Card Checker

## Table of contents

-   [General info](#general-info)
-   [Technologies](#technologies)
-   [Credit Card validation method](#creditcardvalidationmethod)
-   [Setup](#setup)

## General info

Project Goals Context: JS Credit Card Checker provides validation utilities for credit card data inputs. Project would return an object of invalid credit card sorted by company names.

## Technologies

Project is created with:

-   JavaScript

## Credit Card validation method

To find out if a credit card number is valid or not, this project use the Luhn algorithm.

The Luhn algorithm is a series of mathematical calculations used to validate certain identification numbers,

The calculations in the Luhn algorithm can be broken down as the following steps:

1. Starting from the farthest digit to the right, AKA the check digit, iterate to the left.
2. As you iterate to the left, every other digit is doubled (the check digit is not doubled).
3. If the number is greater than 9 after doubling, subtract 9 from its value.
4. Sum up all the digits in the credit card number.
5. If the sum modulo 10 is 0 then the number is valid

## Setup

To run this project, clone it and start index.html

```
$ git clone https://github.com/antoineratat/js_creditcard.git
$ cd js_credit-card-checker
$ node .\main.js
```
