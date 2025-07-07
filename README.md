# Product Table
## Date: 7/7/2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```

<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
</head>
<body>

    <h1>Product Catalog</h1>

    <table border = "1">
        <caption>List of Available Products</caption>
        
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>gaming and study pupose</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>₹18,999</td>
                <td>Daily use</td>
            </tr>

            <tr>
                <td>Headphones</td>
                <td>₹2,499</td>
                <td>Noise cancellation</td>
            </tr>
            <tr>
                <td>Smartwatch</td>
                <td>₹3,999</td>
                <td>Fitness</td>
            </tr>
            <tr>
                <td>Bluetooth Speaker</td>
                <td>₹1,799</td>
                <td>Compact sound</td>
            </tr>
        </tbody>
    </table>

</body>
</html>

```

## Output:

![image](https://github.com/user-attachments/assets/e5bf9d63-6fe1-4d6c-b0cd-15101bd95009)


## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
