# Codsoft_Taskno_3_Contact_Book

# Contact Book with Persistent Storage (Python + JSON)

A user-friendly, command-line-based *Contact Book* application written in *Python*, which allows you to store and manage contact information with *persistent storage using JSON*.

This project is ideal for beginners to understand how to implement *CRUD operations (Create, Read, Update, Delete)* with file handling and basic data structures in Python.

---

## Features

- Add, view, update, delete, and search contacts
- Stores *name*, *phone number*, *email*, and *address* for each contact
- Uses `contacts.json` for *automatic saving and loading* of contact data
- No data is lost after program closes (thanks to persistent storage)
- Clean, menu-driven user interface
- Built with *only standard Python libraries* (no external installation required)

---

## How It Works

1. On launch, the program looks for a `contacts.json` file:
   - If it exists, it loads all previously saved contacts.
   - If not, it creates an empty JSON file automatically.

2. You interact through a *menu system* with numbered options:
   - Add a new contact by entering the required fields.
   - View all stored contacts.
   - Search by name or phone number.
   - Update any contact's details.
   - Delete a contact permanently.

3. All changes are immediately saved back to the JSON file after each operation.

---

## Tech Used

- *Python 3.x*
- Built-in modules:
  - `json` – for reading/writing structured contact data
  - `os` – to check file existence
  - `re` – for optional regex-based search features (if implemented)

No third-party libraries required.

---

Run the script :

```bash
python contact_book.py
