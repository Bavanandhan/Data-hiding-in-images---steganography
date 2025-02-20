Secure Data Hiding in Image Using Steganography

📌 Project Overview
This project focuses on securely hiding sensitive data inside images using **LSB (Least Significant Bit) Steganography** with **AES encryption** for added security. The goal is to ensure confidential data transmission without detection.

🔥 Key Features
AES Encryption: Encrypts messages before hiding them.
LSB Steganography: Embeds data in the least significant bits of image pixels.
Multi-Format Support: Works with PNG, BMP, and JPEG images.
Detection Prevention: Uses adaptive encoding to minimize the risk of discovery.
User-Friendly Implementation: Simple Python script with OpenCV and Cryptography libraries.

🛠️ Technologies Used
Python (Main programming language)
OpenCV (Image processing)
Pillow (PIL) (Image handling)
NumPy (Efficient pixel manipulation)
Cryptography (PyCryptodome) (AES encryption for added security)

🚀 Installation
Make sure you have Python 3.7+ installed. Then, install the required dependencies:

```sh
pip install opencv-python numpy cryptography
```

 📂 Project Structure

📦 Secure-Steganography
 📜 encode.py  # Script to hide encrypted data in an image
 📜 decode.py  # Script to extract and decrypt hidden data
 📜 requirements.txt  # List of dependencies
 📜 README.md  # Project documentation
 📂 images  # Folder for input and output images


🖥️ How to Use
 1️⃣ Encoding (Hiding a Secret Message)
Run the script to hide a secret message inside an image

python encode.py --image input.png --message "Secret Message" --output stego.png


2️⃣ Decoding (Extracting the Hidden Message)
Run the script to extract the hidden message from the image:
```sh
python decode.py --image stego.png
```

## ⚡ Example Usage
```sh
python encode.py --image myphoto.png --message "Confidential Info" --output hidden.png
python decode.py --image hidden.png
```

🛡️ Security Considerations
- Always **keep the encryption key safe**; without it, decryption is impossible.
- Avoid using **highly compressed images (JPEG)** as they may distort hidden data.
- Consider applying **additional encryption** for extra security layers.

📌 Future Enhancements
- ✅ GUI for easy user interaction
- ✅ AI-based steganalysis resistance
- ✅ Support for larger file hiding (beyond text)

📜 License
This project is **open-source** under the MIT License. Feel free to modify and enhance it! 🚀

🤝 Contributing
Contributions are welcome! If you find issues or want to add new features, feel free to submit a pull request.

📞 Contact
For any questions, feel free to reach out:
- 📧 Email: velbavan74@gmail.com
- 🔗 GitHub: [Your GitHub Profile](https://github.com/yourusername)


💡 If you find this project helpful, consider giving it a ⭐ on GitHub!

