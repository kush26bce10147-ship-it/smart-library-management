# smart-library-management
Smart Library Manager - VITyarthi Project(using basic level python program)  A simple command-line program that helps manage the books in a small library. It runs in the terminal and stores all book information in a plain text file.
[README.md](https://github.com/user-attachments/files/32767450/README.md)
# Smart Library Manager

A simple command-line program that helps manage the books in a small library. It runs in the terminal and stores all book information in a plain text file.

## Overview

Smart Library Manager is a beginner-friendly Python project. It lets you add books, view all books, search for a book by title, issue a book to a member, and receive it back when it is returned. All data is saved to a local text file, so the library is remembered even after the program closes.

## Features

- **Add Book** – Add a new book to the library. The book ID is assigned automatically and the new book starts as available.
- **View Books** – Show every book with its ID, title, author, and current status (Available or Issued).
- **Search Book** – Search for books by title. Searching is case-insensitive and partial words work too (for example, "py" matches "Python Basics").
- **Issue Book** – Mark an available book as issued. The program checks that the book exists and is not already issued.
- **Return Book** – Mark an issued book as available again.
- **Save Automatically** – Every change is saved to `books.txt` right away.

## Technologies / Tools

- **Python 3** – The only programming language used (standard library only, no extra packages needed).
- **Text file storage** – Books are stored in `books.txt`, one per line, in the format `id|title|author|available`.
- **Terminal / Command Prompt** – The program is fully operated from the command line.

## How to Install and Run

1. Install **Python 3** on your computer. You can download it from <https://www.python.org/downloads/>.
2. Make sure you have the project files, especially `main.py`, in one folder.
3. Open a terminal (Command Prompt on Windows, or Terminal on macOS/Linux).
4. Go to the project folder:
   - `cd path\to\smart_library`
5. Run the program:
   - `python main.py`
6. Use the numbers in the menu to choose an option:
   - Enter `1` to add a book, `2` to view books, `3` to search, `4` to issue, `5` to return, and `6` to exit.

## Simple Testing Instructions

Testing is done manually through the menu. Try these steps:

1. **View books** – Choose `2` to see the books currently in the library.
2. **Add a book** – Choose `1`, type a title and author, then choose `2` again to confirm the new book appears as Available.
3. **Search** – Choose `3` and type a word from a title (even a partial word) to check the search works.
4. **Issue a book** – Choose `4`, enter the ID of an available book, then choose `2` to see its status change to Issued.
5. **Return a book** – Choose `5`, enter the same ID, then choose `2` to see the status change back to Available.
6. **Exit and reload** – Choose `6`, run `python main.py` again, and choose `2` to confirm the changes were saved in `books.txt`.



