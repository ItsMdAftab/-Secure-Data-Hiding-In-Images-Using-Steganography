# Secure Data Hiding in Images Using Steganography

## Overview
This project implements **LSB (Least Significant Bit) steganography** to securely embed secret messages within images. It provides a **user-friendly GUI** for both encryption and decryption, ensuring a seamless experience for secure data transmission.

## Features
- **Robust LSB steganography**: Embeds passcode and message length within the image header.
- **Lossless data integrity**: Uses PNG format to preserve hidden information.
- **User-friendly GUI**: Simple and intuitive interface for encryption and decryption.
- **Enhanced security**: Combines image processing techniques with secure data transmission.
- **Error handling**: Alerts users if the image is missing or incompatible.

## Target Audience
- **Cybersecurity professionals**: For secure communication methods.
- **Journalists & activists**: Needing covert channels for sensitive information.
- **Students & researchers**: Exploring data privacy and steganography techniques.
- **General users**: Looking to enhance digital security.

## Installation
### Prerequisites
Ensure you have Python installed (>=3.7) and install the required dependencies:
```bash
pip install opencv-python numpy tk
```

### Clone the Repository
```bash
git clone https://github.com/your-username/Secure-Data-Hiding-In-Images-Using-Steganography.git
cd Secure-Data-Hiding-In-Images-Using-Steganography
```

## Usage
### Encryption
1. Run the encryption script:
   ```bash
   python encrypt.py
   ```
2. Enter the **secret message** and **passcode**.
3. The encrypted image will be saved as `encrypted.png`.

### Decryption
1. Run the decryption script:
   ```bash
   python decrypt.py
   ```
2. Enter the correct **passcode** to reveal the hidden message.

## Future Enhancements
- Support for **multiple image formats** and higher resolution images.
- Extend functionality to **video steganography**.
- Implement **advanced encryption algorithms** for added security.
- Develop a **web-based or mobile application**.
- Explore **automated steganographic detection and extraction** tools.

## License
This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

## Contributions
Contributions are welcome! Feel free to fork this repository, create an issue, or submit a pull request.

## Contact
For any queries or suggestions, please reach out via [your email/contact details].

