This is a muti Image steganography project

This project implements a steganography system where multiple images are hidden inside a single image using the **Least Significant Bit (LSB)** method for encoding and **AES-256 encryption** for securing the hidden data. The application includes a web-based interface built with Flask, allowing users to interact with the system for encoding and decoding steganographic data.

Features:
- Hide multiple images within a single cover image.
- Secure hidden images with **AES encryption** for added confidentiality.
- Retrieve and decrypt the hidden images with the correct credentials and key.
- User-friendly interface with Flask for uploading, encoding, and decoding images.
- Implements robust password-derived keys using PBKDF2.

Technologies Used:
- Python
- Flask for web interface
- OpenCV for image processing
- AES encryption (via `pyaes`)
- LSB steganography algorithm

This project demonstrates a secure approach to digital steganography, combining traditional methods with modern cryptographic techniques.
