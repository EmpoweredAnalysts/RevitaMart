# RevitaMart Datasets

This repository contains three datasets for RevitaMart, a fictional online retail company specializing in health and wellness products. 
These datasets are designed to help with customer segmentation, inventory optimization, and sales performance analysis.

## Background

RevitaMart operates globally, offering a variety of products including vitamins, supplements, fitness equipment, and organic foods. 
The datasets included in this repository are synthesized and structured to simulate realistic business scenarios, helping data scientists and analysts practice data manipulation, analysis, 
and machine learning forecasting.

## Datasets

This repository includes the following three datasets found in the Excel file **RevitaMart_Data**:

1. **Customer Data** - Contains information about the customers, such as their IDs, names, emails, gender, birth dates, and geographical details.
   
2. **Sales Data** - Includes transactional data linking customers to the products they purchased, complete with pricing, quantities, and transaction dates.
   
3. **Inventory Data** - Provides details about the product inventory including stock levels, reorder points, and supplier information.

### Data Dictionary

**Customer Data:**
- `CustomerID`: Unique identifier for each customer.
- `FirstName`: First name of the customer.
- `LastName`: Last name of the customer.
- `Email`: Email address of the customer.
- `Gender`: Gender of the customer.
- `DateOfBirth`: Date of birth of the customer.
- `Country`: Country where the customer resides.
- `City`: City where the customer resides.
- `RegistrationDate`: Date when the customer registered.
- `LastPurchaseDate`: Date of the last purchase made by the customer.

**Sales Data:**
- `TransactionID`: Unique identifier for each transaction.
- `CustomerID`: Identifier for the customer.
- `ProductID`: Identifier for the product.
- `ProductName`: Name of the product purchased.
- `Category`: Category of the product.
- `Quantity`: Quantity of product purchased.
- `Price`: Price per unit of the product.
- `TotalAmount`: Total amount spent on the transaction.
- `TransactionDate`: Date when the transaction occurred.
- `PaymentMethod`: Method used for payment.

**Inventory Data:**
- `ProductID`: Unique identifier for each product.
- `ProductName`: Name of the product.
- `Category`: Category of the product.
- `Supplier`: Supplier of the product.
- `CostPrice`: Cost price of the product.
- `SellingPrice`: Selling price of the product.
- `StockQuantity`: Quantity of stock available.
- `ReorderLevel`: Stock level at which reorder is triggered.
- `ReorderQuantity`: Quantity to reorder.
- `LastRestockedDate`: Date when the product was last restocked.

## How to Use
Download the datasets by clicking on the file names.


## License

This project is licensed under the MIT License - see the LICENSE file for details.
