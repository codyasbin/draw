# 🖌️ Advanced Drawing Canvas

A fully interactive **HTML**, **CSS**, and **JavaScript** drawing canvas that allows you to draw, zoom, pan, and manage layers — similar to design tools like **Figma** or **Photoshop**. Built entirely with **vanilla JavaScript**, with no frameworks or external libraries.

---

## 🚀 Features

### 🖋️ Drawing & Tools

* ✏️ **Brush Tool:** Draw freely with adjustable brush size and color.
* 🧽 **Eraser Tool:** Erase parts of your drawing.
* 🟦 **Shapes:** Draw lines, rectangles, and circles *(optional extension).*
* ↩️ **Undo/Redo:** Step backward or forward through your drawing history.

### 🧭 Navigation

* 🔍 **Zoom In/Out:** Use the mouse scroll wheel or pinch (on touch devices).
* 🖱️ **Pan Canvas:** Hold **Spacebar** and drag, or use the **middle mouse button**.
* 🌀 **Double Click:** Reset zoom and position.

### 🧱 Layers

* Create, rename, hide/show, and reorder layers.
* Independent drawing on each layer.
* Adjust layer opacity and blending modes.

### 📐 Canvas Helpers

* **Grid Toggle:** Show/hide a grid background.
* **Snap to Grid:** Align strokes or shapes precisely.
* **Mini-map:** See a zoomed-out view of your canvas.

### 💾 Export Options

* 💡 **Save as PNG** — export as raster image.
* 🧩 **Save as SVG** — export as vector (optional).
* 💾 **Auto-save to Local Storage** — resume your drawing anytime.

---

## 🎮 Controls

| Action      | Shortcut / Mouse              | Description               |
| ----------- | ----------------------------- | ------------------------- |
| Draw        | Left Mouse Drag               | Freehand drawing          |
| Erase       | Right Mouse or `E`            | Switch to eraser mode     |
| Pan         | `Space` + Drag / Middle Mouse | Move the canvas           |
| Zoom        | Mouse Wheel / Pinch           | Zoom in/out around cursor |
| Undo / Redo | `Ctrl + Z` / `Ctrl + Y`       | Undo or redo an action    |
| Reset View  | Double Click                  | Center and reset zoom     |
| Toggle Grid | `G`                           | Show/hide grid            |
| Export PNG  | `Ctrl + S`                    | Save drawing as PNG       |

---

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/advanced-drawing-canvas.git
   ```
2. Navigate to the project folder:

   ```bash
   cd advanced-drawing-canvas
   ```
3. Open the `index.html` file in your browser.

> ✅ No dependencies required — works offline.

---

## 🧩 Project Structure

```bash
📦 advanced-drawing-canvas
├── index.html        # Main HTML file
├── style.css         # Canvas UI styling
├── script.js         # Drawing logic and interaction
└── README.md         # Project documentation
```

---

## 🧠 Future Improvements

* 🟩 Shape tools (rect, circle, polygon)
* 🧠 Selection and transform tools
* 🧵 Vector stroke history for true SVG export
* 🌌 Infinite canvas with dynamic loading
* ☁️ Cloud sync and shareable projects

---

## 📄 License

Released under the **MIT License** — free to use, modify, and distribute.

---

**Made with ❤️ using Pure JavaScript.**
