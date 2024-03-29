The LibraryCLI class serves as the main entry point for the program. It contains a main method that initializes the library catalog and librarian, creates a Scanner object for user input, and presents a menu of options for the user to choose from.
The displayMenu method prints the menu options on the console.
The addBook, addMagazine, and addCD methods handle the process of adding new items (books, magazines, and CDs) to the catalog. They prompt the user for input (such as title, author, and specific item details), create the corresponding objects, and add them to both the catalog and the librarian's list of items.
The removeItem method allows the user to remove an item from the catalog. It prompts for the title and author of the item, searches for a matching item in the catalog, removes it if found, and notifies the user of the outcome.
The LibraryCatalog class represents the catalog of items. It uses an ArrayList to store the items and provides methods to add and remove items from the catalog. It also includes a method to search for an item by its title and author.
The Item class is an abstract class representing a generic item in the library. It has properties for title and author and defines an abstract method getType that subclasses must implement.
The User class is an abstract class representing a library user. It has a name property.
The Librarian class is a subclass of User and represents a librarian. It has methods to add and remove items, although the provided implementation is empty.
The Book, Magazine, and CD classes are subclasses of Item representing specific types of items in the library. They have additional properties specific to each type and implement the getType method.
