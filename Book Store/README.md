# Book Store

This small Tkinter project demonstrates a basic CRUD (Create, Read, Update, Delete) application for managing a collection of books.

## Features

- View all books stored in an SQLite database.
- Search by title, author, year or ISBN.
- Add new entries to the list.
- Update or delete selected entries.
- Simple graphical interface built with Tkinter.

## Setup

1. Ensure Python 3 is installed.
2. Install Tkinter (usually included with Python, but can be installed via pip on some systems):
   ```bash
   pip install tkinter
   ```

## Running the Application

From the `Book Store` directory run:

```bash
python frontend.py
```

The window presents text fields for Title, Author, Year, and ISBN along with buttons to **View all**, **Search entry**, **Add entry**, **Update selected**, **Delete selected**, and **Close**. Selecting an item from the list will populate the fields, allowing updates or deletion.

## Example Usage

Start the program, click **Add entry** to insert a new book, then **View all** to see it listed. You can select any row to edit or remove it. Use **Search entry** to filter the list by keywords or numbers.
