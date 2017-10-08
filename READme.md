##Readme##

Process:

Example: Quantity Label that shows inputed Quantity

In div class containing quantity, include a span class for label.
-Give a new css class: quantity-label, so it can be targeted in the query selector

Grab what we need:
-Create const quantity-label: set it equal to the query selector for the quantity-label class

Create function to update the quantity label:
set quantity label inner text equal to the same number as quantityInput's value

Add Event Listener:
Add quantityInput event listener to listen for input and use the function to update the quantity label
