# CONTACT_BOOK
📇 Contact Book (Python CLI)
An interactive Python command-line contact book that supports adding, viewing, searching, updating, and deleting contact entries in memory.

🚀 Features
CRUD operations: Add, view, search, update, and delete contacts.

Interactive prompts collect contact details: name, phone, email, address.

Simple search by name or phone number (case-insensitive).

In-session persistent list of contacts until the program exits.

User-friendly flow with confirmation prompts and input validation.

🧠 How It Works
Global data structure: Uses a list of dictionaries (contacts) to store contact entries.

Menu-driven interface: Displays menu options, receives user choice, and executes corresponding operation.

Operations:

add_contact(): Prompts user for contact details and appends a new dict.

view_contacts(): Enumerates all stored contacts; handles empty list case.

search_contact(): Accepts keyword, searches name or phone, displays first match.

update_contact(): Finds by name and allows blank input to skip updating fields.

delete_contact(): Finds by name and asks for confirmation before deletion.

Loop control: while True loop until user selects “Exit” (option 6).

Input validation: Validates menu selection and individual contact lookup inputs.

