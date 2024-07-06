ContactManager

Description:
ContactManager is a simple Java application designed to help users manage their contacts. The application allows users to add, view, and store contact information through a console-based interface. The contact information is saved in a text file for persistence.

Files:-
AddContact.java: This file includes the logic to add new contacts. It reads the user's input (name, phone number, email) and stores the contacts in an ArrayList. The contacts are then saved to a file named contacts.txt.
Contact.java: This file defines the Contact class, representing a contact with a name, phone number, and email address. It includes a constructor for initializing these details and getter and setter methods for each field.
Menu.java: This file contains a menu-driven program that offers options to add contacts, view all contacts, or quit the application. It interacts with the user through a menu interface, using the Contact class to manage contact details.

Usage:-
AddContact.java: Run this file to add contacts to the list and save them to contacts.txt.
Menu.java: Run this file to interact with the application through a menu. You can add new contacts or view existing contacts.

Future Enhancements:
Add functionality to delete and update contacts.
Implement a graphical user interface (GUI) for a better user experience.
Improve error handling and input validation.