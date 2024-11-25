# **JAIMIN**  
**Just Automated Inference for Mathematics to Image Notations**  

[![GitHub stars](https://img.shields.io/github/stars/heywinit/JAIMIN)](https://github.com/heywinit/JAIMIN/stargazers)  
[![GitHub issues](https://img.shields.io/github/issues/heywinit/JAIMIN)](https://github.com/heywinit/JAIMIN/issues)  
[![License](https://img.shields.io/github/license/heywinit/JAIMIN)](LICENSE)  

JAIMIN is a Python-based AI system that takes **LaTeX code** as input and generates an **image** simulating **handwritten mathematics**, complete with natural irregularities and imperfections to mimic human handwriting.

## **Features**  
- 🖋️ **Realistic Handwriting Simulation:**  
  Converts mathematical LaTeX code into images that look handwritten, with jittered baselines, slight rotations, and imperfections.  
- 🎨 **Customizable Handwriting Style:**  
  Easily swap handwriting fonts or tweak randomness for personalized output.  
- 🧮 **Seamless LaTeX Rendering:**  
  Renders LaTeX code with precision using Matplotlib.  
- 💻 **Easy to Use:**  
  Straightforward script that can be run locally or integrated into larger projects.  

---

## **How It Works**  
1. **Input:** Provide LaTeX code such as `E=mc^2 + \frac{a}{b}`.  
2. **Rendering:** The LaTeX code is converted into a clean mathematical image.  
3. **Simulation:** Handwriting-like effects are applied, including jitter, irregularities, and pen pressure emulation.  
4. **Output:** A `.png` image resembling handwritten notes is generated.

---

## **Installation**  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/heywinit/JAIMIN.git
   cd JAIMIN
   ```
2. Install Dependencies
  ```
  pip install -r requirments.txt
  ```
3. Ensure LaTeX is Installed
  - Install LaTeX on your system. For example:
    - Windows: MiKTeX
    - Linux/Mac: TeX Live

4. Download a Handwriting Font
    - Download any `.ttf` handwriting font (e.g., from DaFont) and place it in the project directory.
    - Update the `font_path` in the script to point to your font.
  
## **Usage**  

### **Run the Script**  
   ```bash
   python jaimin.py
   ```
### Modify LaTeX Code

- Replace the LaTeX code in the script with your desired expression. For example, in jaimin.py:
  ```py
  latex_code = r"E=mc^2 + \frac{a}{b}"
  ```
### Output:
- The generated image will be saved in the project directory as handwritten_output.png.

## Customization
- Change Handwriting Style:
  - Replace handwriting_font.ttf with another font and update the font_path in the script.
- Tweak Irregularities:
  - Adjust the randomness of jitter and distortions in the simulate_handwriting function to match your preferences.

