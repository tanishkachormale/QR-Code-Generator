# 🎯 Custom GitHub Profile QR Code Generator

This project is a **Python-based tool** that generates a pre-designed QR code for your GitHub profile.  
It has an embed **GitHub logo** in the center and adds your **username** neatly below the QR code, making it perfect for sharing your profile at events, on resumes, or in portfolios.

---

## ✨ Features
- 📌 Generate QR codes from **any GitHub profile URL**.
- 🖼 Embeds a **logo image** in the center of the QR code.
- 📝 Display your **username** below the QR code.
- 🚀 Works instantly — just input URL & username
- 🖨 Save as a **high-quality PNG** file.
- 📱 100% **scannable** with high error correction.

---

## 🛠 Technologies Used
- **Python 3**
- **[qrcode](https://pypi.org/project/qrcode/)** – for generating QR codes.
- **[Pillow (PIL)](https://pypi.org/project/Pillow/)** – for image editing and text rendering.

---
## 📦 Installation

1. **Clone the repository**
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   
2. **Create a virtual environment (optional but recommended)**
   python -m venv venv
   source venv/bin/activate    # On macOS/Linux
   venv\Scripts\activate       # On Windows

3. **Install dependencies**
   pip install -r requirements.txt

4. **Run the script**
   python qr_generator.py

5. **Follow the prompts to enter:**
   Your URL or profile link
   Your username or display text

---

## 📸 Example Output
![QR Code Example](example.png)

---

## 📜 License
This project is licensed under the MIT License — feel free to use and modify it.
