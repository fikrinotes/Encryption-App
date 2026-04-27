# Encryption App

## Introduction

A desktop GUI application built with Python and Tkinter to encrypt text messages from `.txt` files.
It is designed for simple, local use. Select a text file, enter a password, and generate an encrypted output file in the same directory.

## Features

- Desktop interface (Tkinter) with file upload button and password input.
- Encrypts message content from `.txt` files.
- Supports multi-line text files.
- Preserves non-alphabetic characters during one encryption stage.
- Outputs encrypted result to a new file with the ` - encrypted.txt` suffix.
- Shows encryption status in the app window.

## Requirements

- Python 3.8 or newer (recommended)
- `numpy`

## Installation

1. Open your terminal.
2. Clone the repository:

```bash
git clone https://github.com/your-username/encryption-app.git
```

3. Move into the project directory:

```bash
cd encryption-app
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

## How To Use

1. Prepare a `.txt` file that contains the message you want to encrypt.
	Example: `example-text.txt`
2. Run the application:

```bash
python main.py
```

3. In the app window, click the upload icon/button on the left panel.
4. Select your `.txt` file.
5. Enter a password in the right panel.
	Use letters only (no spaces, numbers, or symbols).
6. Click **Encrypt**.
7. If successful, the app shows an `OK` status message.
8. Check the same directory as your source file for the output file.
	The output filename format is:

```text
<original-file-path>/encrypted.txt
```

For example, if your file is `D:/file/example-text.txt`, the encrypted output will be:

```text
D:/file/example-text-encrypted.txt
```

## Notes

- This project currently supports text files (`.txt`) only.
- The app writes the encrypted result as a new file and does not overwrite your original input file.
