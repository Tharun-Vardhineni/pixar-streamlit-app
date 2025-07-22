# pixar-streamlit-app


Here's a human-friendly, professional, and well-structured `README.md` style description for your **Pixor** project — a **Streamlit-based picture editor app**. It's written in the same style as your previous project descriptions:

---

# 🖼️ Pixor – Picture Editor App using Streamlit

## 📘 About the Project

**Pixor** is a lightweight, browser-based **image editing app** built using **Streamlit**. It provides users with simple, intuitive tools to edit and enhance pictures directly in the browser — no installation required!

The app integrates common image processing features such as cropping, resizing, rotating, adding filters, and more — all powered by Python libraries and made accessible through Streamlit's interactive UI.

---

## ❓ What Was the Problem?

Editing images usually requires installing heavy software or using complex tools. For users who want to do **quick edits** like cropping, rotating, or applying filters without any hassle, there aren’t many lightweight or browser-based options.

So the challenge was:

* How can we build a **simple, clean, and responsive** picture editing tool using Python?
* Can we deliver core editing features through a **Streamlit web interface**?

---

## 🎯 What I Aimed to Do

* Build a **user-friendly interface** for editing images
* Use **Streamlit** to serve the application as a web app
* Integrate image processing features like:

  * Resize
  * Crop
  * Rotate
  * Brightness & contrast adjustments
  * Apply filters (grayscale, sepia, blur, etc.)
* Enable users to **upload, preview, edit, and download** images with minimal effort

---

## 🛠️ My Approach (Step-by-Step)

### 1. **Built with Streamlit**

* Streamlit was used for its ease of use and ability to build **interactive apps quickly** in Python
* Designed a clean sidebar layout for user controls

### 2. **Image Upload & Preview**

* Users can upload `.jpg`, `.png`, or `.jpeg` images
* Uploaded images are displayed instantly for preview

### 3. **Editing Features Implemented**

* ✅ **Resize**: Users can define width and height manually
* ✅ **Crop**: Select crop dimensions
* ✅ **Rotate**: Rotate images by 90°, 180°, or custom angles
* ✅ **Adjustments**: Modify brightness, contrast, and sharpness
* ✅ **Filters**:

  * Grayscale
  * Sepia
  * Invert
  * Blur
  * Pencil sketch (optional)

### 4. **Download Edited Image**

* After making changes, users can **download** the edited image with one click
* Images processed in-memory using **PIL (Python Imaging Library)**

---

## 🔬 What I Built

* A fully interactive Streamlit web app
* Clean UI with sidebars for tool controls
* Real-time image preview and editing
* Instant download of the edited image in `.png` format

---

## 🧰 Tools & Libraries Used

* **Python**
* **Streamlit** – for the web interface
* **Pillow (PIL)** – for image manipulation
* *(Optional)*: OpenCV – for advanced filters
* **io**, **base64** – for image display and download

---

## 📌 Key Takeaways

* Streamlit is excellent for building quick data and image apps with minimal code
* Real-time preview makes the UX smooth and intuitive
* PIL and OpenCV offer powerful tools for manipulating images in Python
* The project demonstrates how **backend processing + frontend UI** can be built entirely in Python

---

## 🚀 What’s Next?

* Add more filters like cartoon, emboss, or sketch
* Enable drag-and-drop support for file uploads
* Add image annotation or drawing features
* Deploy to Streamlit Cloud or a custom web server for public access

---
