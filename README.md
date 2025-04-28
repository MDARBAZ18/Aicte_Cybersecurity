# Steganography using Python (cv2)

## ✨ Project Description
This project securely hides a secret message inside an image using pixel value manipulation.  
It ensures that only users with the correct passcode can decrypt and retrieve the hidden message.  
The encryption does not cause any visible change to the image, maintaining secrecy.

## 🚀 Features
- Hide a custom secret message inside an image.
- Protect the message with a passcode.
- Decrypt only if the correct passcode is entered.
- Minimal visual distortion to the image.
- Simple, lightweight, and fast.

## 🛠️ Requirements
- Python 3.x installed

### Required Python library:
```bash
pip install opencv-python
```
## 📂 Project Structure
```
project_supportfiles-main/
│
├── stego.py          # Main Python script
├── mypic.jpg         # Image file (used for embedding message)
└── README.md         # (This file)
```
## ⚙️ Setup Instructions
- Clone or download the project folder.

- Place your image (mypic.jpg) inside the project folder.

- Install OpenCV library if not already installed:

```
pip install opencv-python
```
Run the script:


-python stego.py
Enter your secret message and passcode when prompted.
- example test

## 🖥️ How It Works
- The program reads the image using cv2.imread.

- The message is embedded pixel-by-pixel into the RGB channels.

- A password is required to encrypt and decrypt the message.

- The encrypted image is saved as encryptedImage.jpg.

- Decryption works only with the correct passcode.

## ⚠️ Important Notes
- Ensure that mypic.jpg exists in the same directory as stego.py.

- If the image is missing or the path is incorrect, you will get a NoneType error.

- Keep the secret message short relative to the image size (very large messages can cause errors).
