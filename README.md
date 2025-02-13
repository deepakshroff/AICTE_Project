🛡️ SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY

🔍 Project Description
This project implements image steganography, a technique to securely hide sensitive data within images. 
Using advanced encoding algorithms, we ensure that the hidden data remains undetectable to unauthorized users.

🔑 Key Features:
✅ Data Security - Encrypt and hide confidential information.
🖼️ Image-Based Hiding - Conceal data within PNG, JPG images.
⚡ User-Friendly - Simple encoding & decoding interface.
🔒 Password Protection - Secure access to hidden data.

📌 How It Works?
1️⃣ Encoding (Hiding Data)
Select an image.
Input the secret message/file.
Encrypt and hide it inside the image.


2️⃣ Decoding (Retrieving Data)
Load the stego-image.
Enter the decryption key (if any).
Extract the hidden data.


🖼️ Example:

Original Image                                      	Encoded Image


⚙️ Installation & Setup
📌 Prerequisites:
🔹 Python 3.x
🔹 Required Libraries: numpy, PIL, cv2
   git clone [https://github.com/deepakshroff/AICTE_Project] 
   cd steganography  
   pip install -r requirements.txt  
   python main.py 

 🎮 Usage Guide
🔹 Run the Application:
    python main.py

🔹 Select an option:
    1 Hide Data in Image
    2 Extract Data from Image


📂 Project Structure
📁 Secure-Image-Steganography  
 ┣ 📂 images          # Sample images  
 ┣ 📂 src             # Source code  
 ┃ ┣ 📜 encoder.py    # Encoding logic  
 ┃ ┣ 📜 decoder.py    # Decoding logic  
 ┃ ┣ 📜 gui.py        # User Interface  
 ┣ 📜 README.md       # Documentation  
 ┣ 📜 requirements.txt # Dependencies 


 🛠️ Technologies Used
🚀 Programming Language - Python
🖥️ Libraries - OpenCV, NumPy, PIL

👨‍💻 Contributors
💡 Your Name - deepakshroff

📧 Contact: deepakshroff.code@gmail.com

📜 License
📄 This project is licensed under the MIT License. 
