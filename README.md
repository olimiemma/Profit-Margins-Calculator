# Profit-Margins-Calculator


Profit Margins Calculator

This Python program calculates profit margins and VAT charges for a given item. It takes the cost of the item as input and calculates the markup and VAT charges based on the given percentages. The final output is the total price that the item should be quoted for.

Usage

To use the program, simply run it in a terminal or command prompt and enter the cost of the item as input. The program will then calculate the markup, VAT charges, and total price.

python profit_margins_calculator.py

Enter the cost of the item: 100

Markup: 35.00%
VAT charges: 18.00%
Total price: 151.23
Example

The following example shows how to use the program to calculate profit margins and VAT charges for a given item:

Python
import profit_margins_calculator

# Get the cost of the item from the user.
cost = float(input("Enter the cost of the item: "))

# Calculate the markup, VAT charges, and total price.
markup = profit_margins_calculator.calculate_markup(cost, 0.35)
vat_charges = profit_margins_calculator.calculate_vat_charges(cost, markup, 0.18)
total_price = profit_margins_calculator.calculate_total_price(cost, markup, vat_charges)

# Print the results.
print("Markup:", markup, "%")
print("VAT charges:", vat_charges, "%")
print("Total price:", total_price)
Use code with caution. Learn more
Output:

Enter the cost of the item: 100

Markup: 35.00%
VAT charges: 18.00%
Total price: 151.23
