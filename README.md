# Python-Challenge-1

# Order Management System

## Description

The Order Management System is a Python-based application designed to allow users to place orders from a menu, track the items selected, and generate a receipt with the total cost. The program is interactive, user-friendly, and ensures that the user can easily add items to their order, view their order summary, and complete their purchase.

## Features

- **Menu Display**: The program displays a categorized menu, allowing users to select items from Snacks, Meals, Drinks, and Desserts.
- **Order Placement**: Users can select items from the menu and specify the quantity for each item.
- **Order Summary**: After the order is completed, the program generates and displays a detailed receipt showing each item, its price, quantity, and the total cost of the order.
- **Input Validation**: The program includes input validation to ensure that users enter valid menu options and quantities.

## How to Use

1. **Launch the Program**: Run the Python script to start the order management system.
2. **Select a Menu Category**: The program will prompt you to select a menu category (e.g., Snacks, Meals, Drinks, Desserts).
3. **Choose an Item**: After selecting a category, choose an item from the displayed menu by entering the corresponding item number.
4. **Specify Quantity**: Enter the quantity of the selected item you wish to order. If an invalid input is provided, the quantity will default to 1.
5. **Add More Items**: The program will ask if you want to add more items. You can continue adding items or finalize your order.
6. **View Order Summary**: Once the order is completed, the program will display a receipt with all the items ordered, their prices, quantities, and the total cost.
7. **Exit**: The program ends after displaying the order summary.

## Example Usage

```plaintext
Welcome to the variety food truck.

From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert

Type menu number: 2
You selected Meals

What Meals item would you like to order? 
Item # | Item name                | Price
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49

What menu item would you like? 2
How many Teriyaki Chickens would you like? 2
Added 2 x Teriyaki Chicken(s) to your order.

Would you like to keep ordering? (Y)es or (N)o: N

Thank you for your order!

This is what we are preparing for you.

Item name                    |  Price  | Quantity
-------------------------------------------------
Teriyaki Chicken             |   $9.99 |        2
-------------------------------------------------
Total cost of your order:     |  $19.98
```


### Code contributions note in program comments:
- https://www.youtube.com/watch?v=Tzv3f8eEQdM
- https://www.youtube.com/watch?v=vhlrICrPE1s
- https://www.chatgpt.com
