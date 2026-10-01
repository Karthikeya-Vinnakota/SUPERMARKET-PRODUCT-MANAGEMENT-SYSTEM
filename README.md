# SUPERMARKET-PRODUCT-MANAGEMENT-SYSTEM
SAP ABAP Supermarket Product Management System with CRUD, ALV Report, Selection Screen and Validation.

# Supermarket Product Management System

A beginner-friendly **SAP ABAP project** developed to manage supermarket product information using database operations, ALV reporting, CRUD operations, selection-screen design, and input validation.

## Project Overview

The Supermarket Product Management System allows users to create, read, update, delete, and display supermarket product information stored in a custom SAP database table.

## Features

* Data Dictionary and custom database table
* Insert Product Data
* Display Product Data
* ALV Product Report
* Create, Read, Update and Delete operations
* Selection Screen
* Input Validation
* Duplicate Product ID Validation
* Quantity and Price Validation
* Product Status Validation
* Application Title and Footer

## Technologies Used

* SAP ABAP
* SAP GUI / SAP Logon
* ABAP Dictionary (DDIC)
* Open SQL
* Internal Tables
* Work Areas
* ALV Grid
* Selection Screens
* CRUD Operations
* ABAP Events
* Validation and Error Handling

## Database Table

### `ZSUP_PROD_2515`

The custom table stores supermarket product information such as:

* Product ID
* Product Name
* Category
* Brand
* Unit
* Quantity
* Price
* Supplier
* Expiry Date
* Status

## ABAP Programs

| Program                     | Purpose                         |
| --------------------------- | ------------------------------- |
| `ZINSERT_SUP_PRODUCT_2515`  | Insert product data             |
| `ZDISPLAY_SUP_PRODUCT_2515` | Display individual product      |
| `ZALV_SUP_PRODUCT_2515`     | Display all products using ALV  |
| `ZCRUD_SUP_PRODUCT_2515`    | Create, Read, Update and Delete |
| `ZVALID_SUP_PRODUCT_2515`   | Selection screen and validation |

## CRUD Operations

```text
Create  → INSERT
Read    → SELECT
Update  → UPDATE
Delete  → DELETE
```

## ALV Report

The ALV report displays all products from `ZSUP_PROD_2515` in an SAP ALV Grid.

## Validation

The application validates:

* Product ID
* Product Name
* Category
* Quantity
* Price
* Supplier
* Expiry Date
* Status
* Duplicate Product ID
* Existing Product ID for Update/Delete

## Screenshots

Screenshots of the SAP GUI, database table, CRUD screen, validation messages, and ALV report are available in the `Screenshots` folder.


## Learning Outcomes

This project helped strengthen practical knowledge of:

* SAP ABAP programming
* Database operations
* Open SQL
* Internal Tables and Work Areas
* ALV Reports
* Selection Screens
* ABAP Events
* CRUD operations
* Input validation
* SAP development workflow

## Author

** Vinnakota Hima Naga Karthikeya **

SAP ABAP 

