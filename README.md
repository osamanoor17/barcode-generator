# barcode-generator

This project is a simple Python-based Barcode Generator that creates a barcode image based on user-provided input and saves it to a specified directory.

# Modules to Install
Before running the script, make sure the following libraries are installed:
pip install -r requirements.txt

python-barcode — Used for generating barcodes.

Pillow — Required for saving barcode images in PNG format.

# Purpose of the Code
This tool allows users to generate a barcode image (Code128 format) from text input. It automatically handles directory creation, file saving, and basic error management.

# How It Works
Generating the Barcode:

Uses the Code128 barcode format, suitable for encoding alphanumeric data.

Accepts user input and converts it into a barcode.
Saving the Barcode:

Saves the barcode as a .png image in the Collection/barcode generator directory.

Creates the directory if it does not already exist.
User Interaction:

The user is prompted to enter the data for the barcode.

The image is saved as barcode.png inside the specified directory.
Error Handling:

If saving fails (due to permission issues, path errors, etc.), the script catches the exception and displays an appropriate error message.
Directory Management:

Checks for the existence of the Collection/barcode generator folder.

Creates the folder automatically if it doesn't exist.

# How to Run
python barcode_generator.py
Follow the on-screen prompt to input your desired data for barcode generation.

# Example Output
If you enter:
Enter the data for the barcode: Hello123
The output will be saved as:
Collection/barcode generator/barcode.png
Enjoy generating clean, professional barcodes!
