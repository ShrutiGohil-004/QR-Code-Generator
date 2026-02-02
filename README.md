# QR Code Generator using Python

This project demonstrates how to generate QR codes using Python.  
It includes both a **basic QR code generator** and a **customized QR code generator** with color and high error correction.

---

## 📌 Features

- Generate QR codes from any text or URL
- Save QR codes as PNG images
- Beginner-friendly Python scripts
- Customized QR with color and high error correction

---

## 🛠️ Technologies Used

- Python 3.x
- qrcode library
- Pillow (PIL)

---

## 📂 Project Files

### 1️⃣ simple_qr_generator.py
Creates a basic QR code using minimal code.

**Output:**
- `CodeWithHarry.png`

---

### 2️⃣ custom_qr_generator.py
Creates a customized QR code with:
- Blue color
- White background
- High error correction (can still work if QR is partially damaged)

**Output:**
- `Customized_CodeWithHarry.png`

---

## 🚀 How to Run the Project

### Step 1: Install Required Libraries
```bash
python -m pip install qrcode[pil]
