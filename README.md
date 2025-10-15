# 🔐 Secret Code Generator

This repository contains a simple yet effective **Secret Code Generator** written in Python. [cite_start]The program allows users to encode a plain text message into a secret code and decode it back to its original form using a Caesar cipher algorithm. [cite: 1]

[cite_start]This project is a great exercise for practicing fundamental Python concepts, including functions, loops, string manipulation, and user input handling. [cite: 1]

## 📊 Features

* [cite_start]**Encode & Decode**: Easily transform messages into secret code and back again. [cite: 1]
* [cite_start]**Caesar Cipher Logic**: Uses a substitution cipher where each letter is shifted by a specified number of places in the alphabet. [cite: 2]
* [cite_start]**Case Handling**: Correctly handles both uppercase and lowercase letters. [cite: 2]
* [cite_start]**Character Support**: Ignores non-alphabetic characters like spaces, numbers, and punctuation, leaving them unchanged. [cite: 2]
* [cite_start]**Alphabet Wrapping**: Supports wrapping around the alphabet (e.g., shifting 'Z' by 2 results in 'B'). [cite: 2]
* [cite_start]**Interactive Menu**: A simple command-line menu allows the user to choose between encoding, decoding, or exiting the program. [cite: 1]

## 🚀 How It Works

The program takes a message and a numerical "shift" value. For encoding, it shifts each letter forward in the alphabet by the shift value. For decoding, it performs the reverse operation.

#### Example:

* [cite_start]**Original Message**: `Hello World!` [cite: 8]
* [cite_start]**Shift Value**: `3` [cite: 8]
* [cite_start]**Encoded Message**: `Khoor Zruog!` [cite: 8]

## 💻 How to Use

1.  Clone this repository to your local machine:
    ```bash
    git clone <your-repository-url>
    ```

2.  Navigate to the project directory:
    ```bash
    cd <repository-name>
    ```

3.  Run the script from your terminal:
    ```bash
    python Secret_Code_Generator.py 
    ```
    *(Note: You'll need to save the notebook code as a `.py` file or run it within a Jupyter environment.)*

4.  Follow the on-screen instructions to either encode or decode a message.

    ```
    === Secret Code Generator ===

    Choose an option:
    1. Encode a message
    2. Decode a message
    3. Exit
    Enter your choice (1/2/3): 1
    Enter the message to encode: Hello World!
    Enter shift value (e.g., 2): 3
    Encoded message: Khoor Zruog!
    ```

## 🛠️ Functions Defined

The program is structured around three main functions:

* [cite_start]`encode_message(message, shift)`: Takes a string and an integer shift to produce the encoded message. [cite: 3, 4]
* [cite_start]`decode_message(message, shift)`: Reverses the encoding process by shifting letters backward. [cite: 3, 4]
* [cite_start]`menu()`: Provides the main user interface for interacting with the program. [cite: 3, 6]

## 🔧 Technologies Used

* **Python 3**: The entire program is written in standard Python, with no external libraries required.
