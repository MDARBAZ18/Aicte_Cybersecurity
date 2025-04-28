# SECURE THE DATA TO PREVENT HACKERS

## Overview
This project demonstrates a simple image-based encryption and decryption system. It hides a secret message in an image and allows the message to be decrypted with the correct passcode. The system combines basic cryptography and steganography principles.

## Features
- Encode a secret message into an image using pixel manipulation.
- Password-protected encryption and decryption.
- Decrypt the hidden message by providing the correct password.
- Educational tool for learning encryption and steganography.
- Output is an encrypted image that looks like a normal image.

## Requirements
- Python 3.x
- OpenCV library (`cv2`)

## Installation
1. Install Python from the [official website](https://www.python.org/downloads/).
2. Install OpenCV using pip:
   ```bash
   pip install opencv-python
   ```
### Usage
- Clone the repository or download the code files.

- Place an image in the correct path (use the full path if necessary).

- Run the script:

```bash
python encrypt_decrypt.py
```
- Enter the secret message and password when prompted.

- View the encrypted image and open it to reveal the hidden message by providing the correct passcode.

### Example
- Input:

- Secret message: "Hello everyone"

- Passcode: "123"

### Output:

- An encrypted image with the hidden message.

- Decrypted message: "Hello" after entering the correct passcode.
