# Texture Synthesis by Quilting

This project implements **image texture synthesis** using the **quilting algorithm**, which stitches together small image patches from a source texture to generate a larger synthesized texture. The method ensures seamless blending between patches by finding optimal seams via dynamic programming.

---

## 📌 Project Overview
- **Goal:** Generate realistic large textures from a small texture sample.
- **Method:** Quilting by overlapping patches and minimizing edge discrepancies.
- **Key Feature:** Seam selection is solved with a **shortest path dynamic programming** algorithm, ensuring smooth transitions between patches.

---

## 📂 Files in This Project
- **`4_quilting.ipynb`** → Main Jupyter notebook implementation.
- **`4_quilting.pdf`** → Assignment description.
- **`4_quilting(ans).pdf`** → Solution write-up.
- **`flower.png`, `rock_wall.jpg`, `window.png`** → Example input textures.
- **`README.md`** → Project documentation.

---

## ⚙️ Requirements
This project is implemented in **Python** with the following dependencies:
- `numpy`
- `matplotlib`
- `jupyter`

You can install them with:
```bash
pip install numpy matplotlib jupyter
▶️ How to Run
Open the notebook:

bash
Copy code
jupyter notebook 4_quilting.ipynb
Run all cells in order.

Modify the input texture (e.g., flower.png) to synthesize new textures.

🔑 Key Functions
shortest_path(costs)
Uses dynamic programming to find the lowest-cost seam across an overlap region.

quilt_demo()
Demonstrates texture synthesis by stitching patches together.

📊 Example Results
Synthesized large texture from flower.png

Seamless rock wall extension from rock_wall.jpg

Window texture expansion from window.png

(Example results can be added as images here if available.)

📖 References
This project is based on the Texture Synthesis by Quilting algorithm introduced by Efros & Freeman (2001).

