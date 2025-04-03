# 🔐 Affine Cipher Decryption using Frequency Analysis

## 📌 Overview
This project decrypts Affine Cipher-encrypted text using **frequency analysis** and **probabilistic scoring** to find the most likely plaintext.

## 🛠 Tools Used
- **Python** 🐍  
- String Manipulation  
- Frequency Analysis  

## 📖 How It Works
1. **Brute Force Approach**: Tries all possible key combinations `(a, b)`, where `gcd(a, 26) = 1`.  
2. **Frequency Analysis**: Compares letter frequencies with standard English letter distributions.  
3. **Probabilistic Scoring**: Assigns scores to decrypted outputs based on English word patterns.  
4. **Best Match Selection**: The decryption with the highest score is selected as the final plaintext.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Affine-Cipher-Decryption.git
2. Navigate to the project directory:
   ```bash
   cd Affine-Cipher-Decryption
3. Run the script:
   ```bash
   python decrypt_affine.py
4. Enter the ciphertext when prompted.

5. The script will output the most probable plaintext and the best decryption key (a, b).
   
