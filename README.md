>>> bill_amount = float(input("Enter the total bill amount: $"))
Enter the total bill amount: $54
>>> def determine_total_price(bill_amount):
...     """Determines tip, tax, and total price."""
...     tip_rate = 0.18
...     tax_rate = 0.07
...     tip = bill_amount * tip_rate
...     tax = bill_amount * tax_rate
...     total_price = bill_amount + tip + tax
...     return tip, tax, total_price
...
>>> # Get user input for bill amount
>>> bill_amount = float(input("Enter the total bill amount: $"))
Enter the total bill amount: $54
>>> # Calculate values and show final price breakdown
>>> tip, tax, total_price = determine_total_price(bill_amount)
>>> # Display a well-formatted breakdown of the bill
>>> print("\n====== BILL SUMMARY ======")

====== BILL SUMMARY ======
>>> print(f"Tip:        ${tip:.2f}")
Tip:        $9.72
>>> print(f"Sales Tax:  ${tax:.2f}")
Sales Tax:  $3.78
>>> print(f"Total Cost: ${total_price:.2f}")
Total Cost: $67.50
>>> print("==========================")
==========================
>>>
