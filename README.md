# PixelCipher: Secure Image Encryption

This project is a GUI-based Image Encryption tool built using Python and Tkinter, allowing users to encrypt and decrypt images securely using a passcode.


## Features

- **Encrypt** images with a secure passcode.
- **Decrypt** images using the correct passcode.
- **User-friendly interface** with side-by-side encryption & decryption.
- **Passcode-based security** with hashing for verification.
- **Supports multiple image formats (JPG, PNG, BMP, etc.)**.

## How It Works

### Encryption

1. Select an image.
2. Enter a passcode for encryption.
3. The tool encrypts the image and saves it securely.

### Decryption

1. Select the encrypted image.
2. Enter the correct passcode.
3. The tool decrypts and displays the original image.

## Screenshot

(Add screenshot here)

## Technologies Used

- **Python** (Programming Language)
- **Tkinter** (for GUI)
- **OpenCV (cv2)** (for image processing)
- **Cryptography** (for secure encryption and decryption)
- **Hashlib** (for passcode security)

## Installation & Usage

### Prerequisites

Ensure you have Python installed (preferably Python 3.8 or newer).

### Install Dependencies

Run the following command to install the necessary packages:

```bash
pip install opencv-python cryptography
```

### Running the Application

1. Download or clone this repository.
2. Run the Python script:
   ```bash
   python script_name.py
   ```
3. Use the GUI to encrypt and decrypt images securely.

## License

This project is open-source and available under the MIT License.

## Contributing

Feel free to fork this repository and submit pull requests for improvements or additional features.

