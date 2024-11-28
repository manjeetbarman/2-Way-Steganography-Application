**2-way Steganography Application 🥷**

**Overview 👀**

This repository contains a Python-based application designed to implement 2-way steganography. This technique allows for the secure embedding of data or text within an image 🖼️, and subsequent extraction of the hidden information using a password 🔒.

**Features 🚀**

* **Image Selection 🖼️:** Choose an image to act as the cover medium.
* **Data Input 📝:** Enter the text or data to be hidden.
* **Password Protection 🔒:** Set a password to secure the hidden data.
* **Embedding 🪄:** The application embeds the data within the image, maintaining its visual integrity.
* **Extraction 🔍:** Extract the hidden data from the stego-image using the correct password.

**Installation 🛠️**

1. **Clone the Repository ⬇️:**
   ```bash
   git clone https://github.com/manjeetbarman/2-Way-Steganography-Application.git
   ```
2. **Install Dependencies 📦:**
   Ensure you have Python installed. Then, install the required libraries using pip:
   ```bash
   pip install Pillow opencv-python
   ```

**Usage 🎮**

1. **Run the Application 🏃:**
   Execute the main Python script:
   ```bash
   python main.py
   ```
2. **Follow the Prompts ➡️:**
   The application will guide you through the process:
   - Select an image 🖼️.
   - Choose to embed or extract data 🔄.
   - If embedding, enter the data 📝 and set a password 🔒.
   - If extracting, provide the password 🔑.

**Security Considerations 🛡️**

* **Password Strength 🔐:** Use strong, unique passwords to protect your sensitive data.
* **Image Quality 🖼️:** The quality of the cover image can impact the capacity and security of the stego-image.
* **Steganalysis 🔍:** Be aware of steganalysis techniques that can potentially reveal hidden information.

**Contributing 🤝**

We welcome contributions to improve this application. Feel free to fork the repository, make changes, and submit a pull request.
