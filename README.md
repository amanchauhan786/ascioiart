<img width="671" height="229" alt="image" src="https://github.com/user-attachments/assets/dfac9c28-c16f-4725-8b13-91bbd1640b57" />

````markdown
# Image to ASCII Art Converter  

A simple and fun Python script that converts any image into ASCII art. Just provide the path to your image, and the script will generate a text file (`.txt`) containing the ASCII art representation.  

<!--
IMPORTANT: Add a before-and-after example here!  
Include a source image and a screenshot of the resulting ASCII art text file.  
-->

**Caption:** An example of an image converted into ASCII art.  

---

## 📋 Table of Contents  
- [Features](#-features)  
- [How It Works](#-how-it-works)  
- [Tech Stack](#-tech-stack)  
- [Getting Started](#-getting-started)  
- [How to Use](#-how-to-use)  
- [Future Ideas](#-future-ideas)  

---

## ✨ Features  
- Simple to Use: Straightforward command-line script.  
- Any Image Type: Works with `.png`, `.jpg`, `.jpeg`, etc.  
- Custom Output Name: Specify the output `.txt` file name.  
- Fast Conversion: Quickly generates ASCII art.  

---

## 🧠 How It Works  
The script uses the **pywhatkit** library to handle the image-to-ASCII conversion.  
It maps pixel brightness values to ASCII characters and saves the result into a `.txt` file.  

---

## 🛠️ Tech Stack  
- **Python** – Core programming language.  
- **pywhatkit** – Library providing the ASCII conversion functionality.  

---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.6+ installed on your system.  

### Installation Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/amanchauhan786/ascioiart.git
   cd ascioiart
````

2. (Optional) Create and activate a virtual environment:

   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required library:

   ```bash
   pip install pywhatkit
   ```

---

## ✍️ How to Use

1. Place your image in the project folder.

2. Edit **main.py** and set the file paths:

   ```python
   import pywhatkit as ascii

   source_path = 'your_image_name.jpg'   # <-- CHANGE THIS
   target_path = 'output_ascii_art.txt'  # <-- CHANGE THIS

   ascii.image_to_ascii_art(source_path, target_path)
   ```

3. Run the script:

   ```bash
   python main.py
   ```

4. Open the generated `.txt` file to see your ASCII art! 🎉

---

## 🔮 Future Ideas

* [ ] **Command-Line Arguments** – Allow file paths as input instead of hardcoding.
* [ ] **GUI** – Build a simple interface using Tkinter or PyQt.
* [ ] **Color ASCII Art** – Explore methods to preserve colors in ASCII.

```
