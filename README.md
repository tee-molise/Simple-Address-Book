># Simple-Address-Book
The Simple Address Book is a C-based program designed to help users store and manage personal contact information easily.


🧾 Project Overview

The Simple Address Book is a basic C program designed to manage and organize contact information efficiently.
It allows users to add, view, search, and delete contact records through a simple text-based menu.
Each contact stores a name, phone number, email, and address.

This project demonstrates the use of structures, arrays, and functions in C 

🎯 Features

➕ Add Contact: Store a new contact with name, phone, email, and address.

📋 Display All Contacts: View all saved contacts in a formatted list.

🔍 Search Contact: Search for a specific contact by name.

❌ Delete Contact: Remove a contact from the list.

🚪 Exit: Quit the program safely.

🧠 Learning Outcomes

Through this project, students learn:

How to design and use structures in C.

Implementing menu-driven programs.

Handling string input and comparison.

Managing arrays of user-defined data types.

Writing clean and modular C functions.

⚙️ Technologies Used

Programming Language: C

Compiler: Turbo C++ / DOSBox (for legacy C support)

Concepts: Structures, Arrays, Loops, Functions, Input/Output handling

💻 System Requirements

Hardware:

Minimum 1 GB RAM

500 MB storage space

Software:

Turbo C++ compiler or any C IDE (e.g., Code::Blocks, Dev-C++, GCC)

DOSBox (if using Turbo C++ on modern Windows)

🚀 How to Run the Program

Download or clone this repository:

git clone https://github.com/tee-molise/simple-address-book.git


Open the file address_book.c in Turbo C++ or your preferred C compiler.

Compile and run the program.

Follow the on-screen menu options to add, view, search, or delete contacts.

📸 Sample Output
<img width="346" height="180" alt="Screenshot 2025-11-03 234529" src="https://github.com/user-attachments/assets/36413c15-f047-4b70-82fb-34997a061425" />

Enter your choice: 1

<img width="302" height="317" alt="image" src="https://github.com/user-attachments/assets/9b2c21dd-19ee-473e-b7c1-d002c5241e35" />

🧾 Example Data Structure
struct Contact {
    char name[50];
    char phone[15];
    char email[50];
    char address[100];
};

🧩 Future Enhancements

Implement file handling to save and load contacts permanently.

Add sorting options (alphabetically or by phone number).

Build a graphical user interface (GUI) version using C++ or Python later.

Create a mobile app version for easier access.

Author

Name: Tlhoriso Molise(25BCA20025),Jaskirat Singh,Mansahaj Sigh,Rishab Mohan

Course: BCA(AR and VR)
Year: First Year
