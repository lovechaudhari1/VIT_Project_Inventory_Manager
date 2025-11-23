Project Report: Simple Inventory Manager
Introduction
The Simple Inventory Manager is a Python-based command-line application designed to help users manage a collection of inventory items efficiently. It allows users to add new items, update existing stock quantities, view details of specific items, and list all inventory items actively maintained in the system.

Objectives
To maintain an organized list of inventory items with details such as item code, name, quantity, and price.

To provide easy-to-use functions for adding new items, updating stock, viewing item details, and listing the complete inventory.

To provide a simple, interactive interface accessible via the command line.

Features
Add Item: Users can add new items to the inventory by supplying a unique code, a name, initial quantity, and price.

Update Stock: Existing item quantities can be increased or decreased by specifying the item code and adjustment quantity.

View Item: Detailed information about a specific item (code, name, quantity, price) can be retrieved using the item's unique code.

List Inventory: Users can view a list of all current inventory items with their respective quantities and prices.

Exit: Option to exit the program cleanly.

System Design
The program is designed using a class SimpleInventory that encapsulates the inventory data as a dictionary storing items with their associated details.

Each inventory item is stored as a dictionary entry: the key is the item code (a unique identifier), and the value is another dictionary containing the item's name, quantity, and price.

All operations (add, update, view, list) are implemented as methods within this class, ensuring modularity and easy maintenance.

User Interaction
The program runs an infinite loop displaying a menu of options for the user.

Through simple user inputs, users choose actions, provide necessary details, and receive immediate feedback on operations.

Input validation includes checking for existing item codes during addition and checking item presence before updates or views.

Advantages
Simplicity: The code is straightforward and easy to understand, making it accessible for beginners.

Interactivity: Command-line prompts guide the user through managing inventory without requiring additional interface tools.

Extensibility: The design lends itself to adding more features in future, such as file/database persistence, reporting, and graphical interfaces.

Limitations
The inventory data exists only in memory; no data storage or persistence means data is lost when the program exits.

No advanced error handling for invalid input types (e.g., non-numeric quantities).

The uniqueness of item codes relies on user input and is not programmatically enforced beyond checking for duplicates.

Possible Improvements
Add persistent storage using files or a database to save inventory data across sessions.

Implement input validation and exception handling to make the program more robust.

Add search and sort capabilities for ease of item retrieval.

Introduce a graphical user interface to improve user experience.

Conclusion
This Simple Inventory Manager demonstrates basic inventory management functionalities in Python using object-oriented principles. It is a practical tool for managing small inventories and provides a solid foundation for building more sophisticated inventory systems. The program's clarity and modular design make it well-suited for educational purposes and small-scale applications.
