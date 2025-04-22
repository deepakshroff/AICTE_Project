# Secure Data Hiding in Images using Steganography

## 📘 Project Overview

This project demonstrates how to securely hide sensitive data within digital images using image steganography. The system allows encoding and decoding of hidden information with optional encryption, ensuring secure communication and data concealment.

---

## 🔐 Features

- **Data Security:** Encrypt and embed confidential messages or files into image files.
- **Image-based Hiding:** Works with PNG and JPG image formats.
- **User-friendly Interface:** Simplified encoding and decoding process.
- **Password Protection:** Secure the decoding process using a decryption key.

---

## 🔧 How It Works

### 1. Encoding (Hiding Data)
- Upload/select an image.
- Enter the message or upload the file to hide.
- Encrypt and embed the data into the image.
- Save the output stego-image.

### 2. Decoding (Extracting Data)
- Load the stego-image (image containing hidden data).
- Provide the correct password/key (if enabled).
- The system extracts and decrypts the hidden content.

---

## 🧪 Technologies Used

- **Programming Language:** Python 3.x
- **Libraries:** `numpy`, `Pillow (PIL)`, `OpenCV (cv2)`

---

## 📂 Project Structure

AICTE_Project-main/
- ├── encode.py           # Script to hide data in an image.
- ├── decode.py           # Script to extract data from image.
- ├── requirements.txt    # Python dependencies.
- ├── sample_images/      # Folder for input/output images.
- └── README.md           # Project documentation.

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.x installed on your system

### Clone the Repository
```bash
git clone https://github.com/deepakkumar-ai/AICTE_Project-main
cd AICTE_Project-main
