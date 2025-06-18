# Steganography – Hiding Information in the Image 🔐🖼️

## 💡 Project Overview

This project is developed as part of the AICTE–IBM 6-week internship on Cybersecurity. It focuses on **Steganography**, the technique of hiding sensitive information within an image to ensure data confidentiality and secrecy.

Here, we've implemented a secure pipeline using:
- **ASCII XOR Encryption** – to encrypt the secret message
- **Least Significant Bit (LSB) Image Steganography** – to hide the encrypted message within an image

> The goal: Make private messages invisible to the naked eye, but retrievable with a key!

---

## 🚀 Technologies Used

- **Python 3.10+**
- **Jupyter Notebook (VS Code)**
- **Pillow (PIL)** – for image manipulation

---

## 🔐 Techniques Implemented

### 1. **XOR Encryption**
- Lightweight symmetric encryption technique
- Each character of the message is XORed with a single-character key

### 2. **Text-to-Binary Conversion**
- The encrypted message is converted into binary (0s and 1s) before embedding

### 3. **LSB Image Steganography**
- Embeds message bits in the least significant bits of pixel RGB values
- Uses a delimiter (`11111110`) to mark the end of the message

---

## 📂 Folder Structure

steganography_project/
├── data/
│ ├── input_image.png # Original image
│ ├── stego_image.png # Output image with hidden data
├── Steganography_Project.ipynb # Main notebook with code and tests
├── README.md # This file


---

## 🧪 How to Run

1. Open `Steganography_Project.ipynb` in **VS Code** (Jupyter Extension).
2. Run all cells step-by-step.
3. Provide:
   - `input_image.png` inside the `data/` folder
   - Your message and XOR key
4. The stego image will be saved as `stego_image.png`
5. Use the decoder function to retrieve and decrypt your hidden message.

---

## ✅ Sample Output

✅ Message encoded and saved as data/stego_image.png
🔓 Decoded Message: Hello Jassuu, your internship is 🔐 on point!

---

## 📌 Real-World Applications

- Secure communication over open channels
- Digital watermarking and anti-tampering
- Military and Intelligence data hiding
- Journalistic data protection in oppressive regimes

---

## 🙋 Author

**Shaik Jasmin**  
🎓 AICTE – IBM Internship, Cybersecurity 
🛡️ Project: Steganography Using XOR & LSB

---

## 🔐 Disclaimer

This is an academic project built for educational purposes. While XOR and LSB techniques demonstrate the concept well, they are not considered secure for industrial-strength applications.

---


