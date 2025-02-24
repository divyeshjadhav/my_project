Overview
This project implements image steganography, allowing users to hide secret messages within image pixel values. It ensures covert communication with an added password-based authentication for secure decryption.

Technologies Used
Python – Core programming language
OpenCV (cv2) – Image processing for embedding messages
OS Module (os) – File handling operations

How It Works
For intalling (cv2):
In command prompt enter 'pip install opencv-python' and click enter.

Encryption:

User inputs a secret message and passcode.
The message is encoded into pixel values of an image.
The modified image (encryptedImage.jpg) is saved.

Decryption:

User enters the correct passcode.
The message is retrieved from pixel values and displayed.

Features:
Steganography-based message hiding
Password-protected decryption
Lightweight & efficient image processing
Potential for enhanced encryption (e.g., RSA)
