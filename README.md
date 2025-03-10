# Billing-System-Basic-to-Advance
# Billing System (Basic)
### Data Entry:

Prompts the user to enter the number of products (size).

Uses a loop to collect product names and their respective prices.

For each iteration, asks for the product name and appends it to the product list.

For each iteration, asks for the product price and appends it to the price list.

### Processing:

Stores product names in a list called product.

Stores prices in a list called price.

### Output:

Uses a loop to display each product with its corresponding price.

Displays a simple bill showing product names and prices.

# Billing System (Basic) with GST
### Data Entry:

Prompts the user to enter the number of products (size).

Uses a loop to collect product names and their respective prices.

For each iteration, asks for the product name and appends it to the product list.

For each iteration, asks for the product price and appends it to the price list.

Asks the user if they want to add GST (user input).

If GST is to be included, asks for the GST percentage (gst).

### Processing:

Stores product names in the product list.

Stores prices in the price list.

Calculates the total amount by summing up the prices.

If GST is to be added:

Calculates the GST amount by applying the GST percentage to the total amount.

Calculates the final amount by adding the GST amount to the total amount.

### Output:

Uses a loop to display each product with its corresponding price.

Displays the total amount, GST percentage, GST amount, and final amount if GST is included.

If GST is not included, simply displays the total amount as the final amount.

# Advance Billing System
### Data Entry:

Prompts the user to enter the number of products (size).

Uses a loop to collect product names and prices, and optionally allows the user to add more products.

For each iteration, asks for the product name and appends it to the product list.

Provides an option to add more products by asking the user (user input).

If the user decides to stop adding products, the loop breaks.

For each iteration, asks for the product price and appends it to the price list.

Asks the user if they want to add GST (user input).

If GST is to be included, asks for the GST percentage (gst).

### Processing:

Stores product names in the product list.

Stores prices in the price list.

Calculates the total amount by summing up the prices.

If GST is to be added:

Calculates the GST amount by applying the GST percentage to the total amount.

Calculates the final amount by adding the GST amount to the total amount.

### Output:

Uses a loop to display each product with its corresponding price.

Displays the total amount, GST percentage (if applicable), GST amount (if applicable), and final amount.

If GST is not included, simply displays the total amount as the final amount.

# Super Advance Billing System
### Data Entry:

Prompts the user to enter the number of products (size).

Uses a loop to collect product names, prices, and quantities, and optionally allows the user to add more products.

For each iteration, asks for the product name and appends it to the product list.

Asks for the product price and appends it to the price list.

Asks for the quantity of the product (QT) and stores it.

Provides an option to add more products by asking the user (user input).

If the user decides to stop adding products, the loop breaks.

Asks the user if they want to add GST (user input).

If GST is to be included, asks for the GST percentage (gst).

Asks the user if they want to apply an offer (user input).

If an offer is to be applied, provides options (2%, 4%, 8%) and asks the user to select one (offers).

### Processing:

Stores product names in the product list.

Stores prices in the price list.

Stores quantities.

Calculates the total amount by summing up the product of prices and quantities.

If GST is to be added:

Calculates the GST amount by applying the GST percentage to the total amount.

Adds the GST amount to the total amount to get an intermediate amount.

If an offer is to be applied:

Calculates the discount amount by applying the offer percentage to the intermediate amount.

Subtracts the discount amount from the intermediate amount to get the final amount.

If no offer is applied, the final amount is the intermediate amount after adding GST.

### Output:

Uses a loop to display each product with its corresponding price and quantity.

Displays the total amount, GST percentage (if applicable), GST amount (if applicable), offer percentage (if applicable), and final amount after applying GST and selected offer.

If no GST is included, displays the total amount and final amount after applying the offer (if applicable).

Each system progressively adds more functionality, from a simple bill to advanced calculations involving GST and discounts, allowing for a flexible and comprehensive billing solution.
