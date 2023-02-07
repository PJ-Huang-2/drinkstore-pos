# drinkstore-pos
This script is a simple implementation of an AlphaPos system, which is a web-based point of sale (POS) system for a cafe/drink shop.

The system has several features:

Ordering a drink: When the addDrinkButton is clicked, the system retrieves the selected values of the drink item, sugar, and ice options. If no drink item is selected, an alert message will be displayed. A drink instance will then be created with the selected options and its price will be calculated. The drink instance will then be added to the order list on the left side of the page.
Deleting an ordered drink: An event listener is added to the order list, and when a delete button on a card in the order list is clicked, the corresponding drink card will be removed from the order list.
Checking out the order: When the checkout button is clicked, the total amount of the order will be calculated and displayed in an alert message. A confirm dialog will then pop up to confirm the checkout, and if confirmed, the order list will be cleared.
Additionally, there are two constructor functions:

AlphaPos: This constructor defines several methods for the AlphaPos system, including getCheckedValue, addDrink, deleteDrink, and checkout.
Drink: This constructor creates a drink instance with the specified name, sugar, and ice options.

<h4>Please <a href="https://pj-huang-2.github.io/drinkstore-pos/">Check this out</a></h4>
