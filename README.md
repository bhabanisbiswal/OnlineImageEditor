---

# 🖼️ Online Image Editor

A simple **Flask web application** that allows users to upload images and perform basic processing using **OpenCV**.
With just a few clicks, you can convert your images to **grayscale** or change their format to **PNG**, **JPG**, or **WEBP** — all handled securely.

---

## ✨ Features

### 🖼 Image Upload

* 📤 Upload images in multiple formats: **PNG**, **JPG**, **JPEG**, **WEBP**, **GIF**.
* 🔒 Secure file handling using `secure_filename()`.

### 🎨 Image Processing

* ⚫ **Grayscale Conversion** (`cgray`) – Turns the image into black & white.
* 🌐 **WEBP Conversion** (`cwebp`) – Compress images with modern format.
* 🖼 **JPG Conversion** (`cjpg`) – Save in JPG format.
* 📷 **PNG Conversion** (`cpng`) – Save in PNG format.

### 📥 Output

* 🗂 Processed images are stored in the `static/` folder.
* 🔗 Direct download links after processing.

---

## 🛠 Tech Stack

* 🐍 **Python**
* 🌐 **Flask** – Web backend.
* 🎥 **OpenCV** – Image processing.
* 🖥 **HTML + Jinja2 Templates** – Frontend rendering.

---

## 📂 Project Structure

```
OnlineImageEditor/
│── app.py              # Main Flask application
│── templates/          # HTML templates
│── static/             # Processed images
│── uploads/            # Uploaded images
│── requirements.txt    # Python dependencies
│── README.md           # Project documentation
```

---

## ⚙ How It Works

1️⃣ **Upload** an image using the web form.
2️⃣ Choose a processing option:

* `cgray` → Grayscale
* `cwebp` → Convert to WEBP
* `cjpg` → Convert to JPG
* `cpng` → Convert to PNG
  3️⃣ **Processed image** is saved in `static/` folder with a **direct download link**.

---

## 📥 Installation

1. 📂 Clone the repository:

```bash
git clone https://github.com/your-username/image-processing-flask.git
```

2. 📁 Navigate into the folder:

```bash
cd image-processing-flask
```

3. 📦 Install dependencies:

```bash
pip install flask opencv-python
```

4. 📂 Create necessary folders:

```bash
mkdir uploads static
```

5. ▶ Run the application:

```bash
python app.py
```

6. 🌐 Open in browser:

```
http://127.0.0.1:5001
```

---

## 🚀 Usage

* 📤 Upload your image from the homepage.
* 🎯 Choose the desired processing option.
* 📥 Download the processed image directly.

---

## 📸 Demo

*
*Project Frame

![img_alt](https://github.com/bhabanisbiswal/OnlineImageEditor/blob/de233f492e2a66f9f324d2eae6dbfbf58579924f/project_image1.png).
![img_alt](https://github.com/bhabanisbiswal/OnlineImageEditor/blob/de233f492e2a66f9f324d2eae6dbfbf58579924f/project_image2.png).

*sample input 

![img_alt](https://github.com/bhabanisbiswal/OnlineImageEditor/blob/0b834b62827c22585cf1ffb031ac154efaeac4c6/uploads/vlcsnap-2025-01-03-21h17m03s144.png)

*Sample Output

![img_alt](https://github.com/bhabanisbiswal/OnlineImageEditor/blob/de233f492e2a66f9f324d2eae6dbfbf58579924f/output.png).


*

---

## 🔮 Future Improvements

* 🖌 Add filters (blur, sharpen, sepia, etc.).
* 📦 Zip multiple processed images for batch download.
* 📱 Mobile-friendly responsive design.
* 🗜 Adjustable image compression level.

---

## 👤 Author

**Bhabani S Biswal** – Python & AI/ML Developer
📧 Email: [bhabanibiswalb17@gmail.com](mailto:bhabanibiswalb17@gmail.com)
🔗 GitHub: [Bhabani S Biswal](https://github.com/bhabanisbiswal)

---

