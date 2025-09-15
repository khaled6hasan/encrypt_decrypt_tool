# AnyCript Pro


**AnyCript Pro** is an all-in-one utility tool for cryptography, file encryption, and financial calculations. Built with **React**, **TailwindCSS**, and modern **Web Crypto APIs**, this app provides a clean, responsive, and secure interface for users to handle encryption tasks and financial calculations efficiently.

---

## Features

### **Cryptography Tools**
- **AES-GCM Encryption & Decryption** with password protection
- **SHA-256 Hashing**
- **PBKDF2 Key Derivation**
- **Base64 Encode & Decode**
- Customizable **PBKDF2 iterations**
- Easy-to-use input/output interface

### **File Tools**
- Encrypt and decrypt files securely
- Password-protected file encryption
- Progress indicator for encryption/decryption
- Original filename preservation on decryption

### **Financial Calculators**
- **Fixed Deposit (FD) Calculator**
- **Systematic Investment Plan (SIP) Calculator**
- Shows maturity, interest, total invested, and estimated earnings

### **Other Features**
- **Dark Mode** toggle
- Smooth animations & responsive design
- All computations done **client-side** (no server needed)
- Modern and user-friendly interface

---

## Demo

You can try the live demo by opening the `index.html` in your browser.

---

## Installation

### 1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/anycript-pro.git
 ```
### 2. Navigate to the project folder:

 ```bash
cd anycript-pro
 ```

### 3. Open index.html in your browser (no server required).

---

## Usage
### 1. Cryptography

- Enter your text and password.
- Choose the desired cryptography function (AES, SHA-256, PBKDF2, Base64).
- Click the corresponding button to get the output.

### 2. File Tools

- Select a file from your device.
- Enter your password and optional PBKDF2 iterations.
- Click Encrypt File or Decrypt File.
- Download the processed file.

### 3. Financial Calculators

- Enter principal, rate, and duration for FD or monthly investment, rate, and months for SIP.
- Click Calculate to see results.

---

## Screenshots

![encryption_decryption](https://github.com/khaled6hasan/encrypt_decrypt_tool/blob/main/encryption_decryption.PNG)
---

## Technologies Used

- React 18 (Functional Components & Hooks)
- TailwindCSS for responsive design
- Babel Standalone for JSX compilation
- Web Crypto API for encryption, hashing, and key derivation
- Vanilla JavaScript & HTML

---

## Contributing

Contributions are welcome! Please follow these steps:
- Fork the repository
- Create a new branch ( ```git checkout -b feature/YourFeature ```)
- Make your changes
- Commit your changes ( ```git commit -m 'Add your feature' ```)
- Push to the branch ( ```git push origin feature/YourFeature ```)
- Open a Pull Request

---

## License
This project is licensed under the MIT License - Feel free to use and modify!

---

## Author

Khaled Hasan Nahid 
 
---

## Note: 
All encryption and calculation operations are performed locally in your browser. Never use sensitive real-world passwords for testing.
