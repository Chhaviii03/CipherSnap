AN IMAGE ENCRYPTION DECRYPTION WEB APP. STILL IN THE WORKS

Overview
This project is a Python-based image processing application featuring a graphical user interface (GUI) built with Tkinter. It leverages libraries like OpenCV to provide functionality for encrypting images into grayscale format and decrypting them back to their original state. Users can also save processed images locally, making it a complete tool for secure image handling.

Key Features
Image Encryption and Decryption:

Encrypt images by converting them to grayscale.
Decrypt images to restore their original appearance.
User-Friendly GUI:

Designed with Tkinter for an intuitive interface, including buttons to select, encrypt, decrypt, save, reset, and exit.
Flexible File Handling:

Allows saving processed images to a user-specified directory.
Provides a reset option to revert to the original image.
Advanced Image Processing Tools:

Utilizes NumPy, Pillow (PIL), and OpenCV for efficient image manipulation and visualization.
Technology Stack
Programming Language: Python 3
Libraries and Modules:
Tkinter: GUI design
OpenCV: Image processing
NumPy: Numerical computations
Pillow (PIL): Image handling
Random and OS: File operations
How to Use
Install the required dependencies using pip:
Copy
Edit
pip install opencv-python-headless numpy pillow
Run the application script:
Copy
Edit
python image_encryption_decryption.py
Use the GUI to:
Load an image.
Encrypt or decrypt it.
Save the processed image or reset it to the original.
Purpose
The project enhances image security by providing a simple yet effective way to encrypt sensitive images and decrypt them when needed, ensuring data privacy and flexibility.
