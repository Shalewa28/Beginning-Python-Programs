# This code comes from Chapter 4 of: Matthes, E. (2023). 
# Python Crash Course (3rd ed.). No Starch Press.

# Defining a tuple of buffet menu items
buffet_menu = ("Jollof Rice", "Grilled Chicken", "Salad", "Pasta", "Fried Plantains")

# Printing each item in the buffet menu
print("Original Buffet Menu:")
for item in buffet_menu:
    print(f"- {item}")

# Attempting to modify an item in the tuple (This will raise an error)
# buffet_menu[0] = "Fried Rice"  # Uncommenting this line will cause a TypeError

# Correct way to change the menu: redefine the tuple
buffet_menu = ("Fried Rice", "Grilled Chicken", "Vegetable Stir-fry", "Pasta", "Roasted Yam")

# Printing the updated menu
print("\nUpdated Buffet Menu:")
for item in buffet_menu:
    print(f"- {item}")
