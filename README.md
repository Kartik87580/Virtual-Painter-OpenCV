
````markdown
# 🎨 Virtual Painter using OpenCV

This project is an **interactive virtual painting app** built using **Python** and **OpenCV**.  
By using **color detection**, you can control a virtual brush in real-time with any colored object (like a marker or cap) and draw on the screen.  

It also provides an on-screen **color palette** to switch between Blue, Green, Red, and Yellow brushes, along with a **Clear All** option.

---

## 📌 Features
- 🎥 Real-time drawing using webcam tracking.
- 🖌️ Draw with different colors: **Blue, Green, Red, Yellow**.
- 🧽 Clear the entire canvas instantly.
- 🎚️ Adjustable HSV ranges using OpenCV trackbars for better marker detection.
- 🖼️ Dual View: Live camera feed + Canvas.

---

## 🛠️ Requirements
Make sure you have **Python 3.7+** installed and install the required libraries:

```bash
pip install opencv-python numpy
````

---

## 📂 Project Structure

```
VIRTUAL PAINTER/
│── app.py          # Main Python script for virtual painting
│── README.md       # Project documentation
```

---

## 🚀 How to Run the Project

### **Step 1 — Clone or Download**

```bash
git clone https://github.com/yourusername/virtual-painter.git
cd virtual-painter
```

### **Step 2 — Run the App**

```bash
python app.py
```

---

## 🎨 How It Works

1. **Color Detection**

   * The app detects a colored marker using HSV values from your webcam feed.
   * You can adjust the detection range using the **trackbars**.

2. **Draw on Canvas**

   * Move the detected colored object in front of your camera.
   * The app tracks the position and draws lines accordingly.

3. **Change Brush Colors**

   * Choose between **Blue, Green, Red, or Yellow** by hovering your marker over the color buttons at the top.

4. **Clear Canvas**

   * Hover over the **CLEAR ALL** button to erase everything.

---

## 🎛️ On-Screen Controls

| **Button** | **Action**               |
| ---------- | ------------------------ |
| CLEAR ALL  | Clears the entire canvas |
| BLUE       | Switch brush to Blue     |
| GREEN      | Switch brush to Green    |
| RED        | Switch brush to Red      |
| YELLOW     | Switch brush to Yellow   |

---

## 🧠 Concepts Used

* **OpenCV** for video capture, image processing, and drawing.
* **HSV Color Space** for better object detection.
* **Morphological Transformations** for noise removal.
* **Contours & Moments** to track the center of the detected object.
* **Deque** for smooth brush stroke handling.

---

## 🎥 Demo

* Place a **colored marker** in front of your webcam.
* Adjust HSV values using trackbars until only your marker is detected.
* Start moving your marker to draw on the virtual canvas.
* Press **'q'** to exit the app.

---

## ⚠️ Tips for Best Results

* Use a **solid-colored marker or cap** for better detection.
* Prefer a **plain background** to reduce noise.
* Adjust HSV values based on **lighting conditions**.

---

## ✨ Author

**Kartik Jambucha**
📌 *Made with OpenCV, NumPy & Python for fun and learning* 🚀

```



```
