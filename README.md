AutoCryptor 🔐

An intelligent C++ text encryption and decryption system that automatically detects input format and applies the correct cipher using efficient data structures.

Built with Binary Trees and Hash Tables to ensure fast lookups, structured encoding, and clean decoding — all without external libraries.

🌟 Features

🔍 Automatic Text Detection – Identifies whether input text is encoded or decoded
🔐 Smart Encryption & Decryption – Applies transformations based on a cipher file
🌳 Binary Tree Encoding – Efficient character mapping using tree traversal
🗂️ Hash Table Lookup – Constant-time access for cipher substitutions
📄 File-Based Processing – Works directly with .txt files
⚡ Fast Performance – Optimized using classic data structures
🧠 Data Structures in Action – Practical application of trees & hash tables
💻 Pure C++ Implementation – No external libraries required

💻 Tech Stack

C++ – Core implementation

Binary Trees – Encoding & decoding logic

Hash Tables – Cipher mapping and fast lookups

File I/O – Input/output text processing

🚀 Getting Started
Prerequisites

C++ Compiler (g++, clang, or equivalent)

Terminal / Command Line

Linux, macOS, or Windows (WSL recommended)

Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/AutoCryptor.git

cd AutoCryptor/codeforlab3introdatastructures


Compile the program:

g++ main(2).cpp manager.cpp binary_tree.cpp hashtable.cpp -o AutoCryptor


Run the program:

./AutoCryptor

📂 Project Structure

AutoCryptor/

├── binary_tree.cpp / .h     # Tree-based encoding logic

├── hashtable.cpp / .h       # Fast cipher lookup

├── manager.cpp / .h         # Program control flow

├── main(2).cpp               # Entry point

├── cipher.txt                # Cipher definition file

├── test1.txt / test2.txt     # Sample input files

