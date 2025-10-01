# task4
 A simple Java CLI-based Notes App that lets you create and read notes from a file using FileWriter and BufferedReader
: Features

Add new notes (saved into notes.txt)

View all saved notes

Data is stored persistently using file handling
 How to Run

Clone the repo

Compile the program:

javac NotesApp.java


Run the program:

java NotesApp
: What I Did

Used FileWriter (append mode) to save notes.

Used BufferedReader + FileReader to display saved notes.

Handled exceptions with try-catch and try-with-resources.

Practiced File I/O and Exception Handling in Java.
: Example Run
: === Notes App Menu ===
1. Add Note
2. View Notes
3. Exit
Enter choice: 1
Enter your note: Call the electrician in the evening
Note saved successfully!

=== Notes App Menu ===
1. Add Note
2. View Notes
3. Exit
Enter choice: 1
Enter your note: Buy tickets for the weekend movie
Note saved successfully!

=== Notes App Menu ===
1. Add Note
2. View Notes
3. Exit
Enter choice: 2

--- Your Notes ---
- Call the electrician in the evening
- Buy tickets for the weekend movie
