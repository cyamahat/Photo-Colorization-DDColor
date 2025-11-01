# 🖼️ Photo Colorization with DDColor

This repository demonstrates how to colorize black-and-white photos using **DDColor**, a deep learning model for high-quality automatic image colorization.  
It includes a simple **Jupyter Notebook** to test the model on sample grayscale images.

---

## 📘 Overview

- **Framework**: [ModelScope](https://modelscope.cn) (with DDColor)  
- **Interface**: Jupyter Notebook (tested in VS Code 1.105)  
- **OS Tested**: Windows 10  
- **Date Tested**: November 2025  
- **Purpose**: Simple demonstration of automatic colorization using the DDColor model through ModelScope.

---

## 🧩 Features

- Automatically colorize black-and-white photos.  
- Uses the pre-trained **DDColor** model from ModelScope.  
- Simple notebook-based workflow for experimentation.  
- No manual model downloads — ModelScope handles model loading automatically.

---

## ⚙️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/cyamahat/Photo-Colorization-DDColor.git
   cd Photo-Colorization-DDColor
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install "modelscope[cv]" timm opencv-python matplotlib
   ```

   *(This includes the necessary packages for this notebook: ModelScope, DDColor, OpenCV, and Matplotlib.)*

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Then open the notebook file `Photo-Colorization-DDColor.ipynb`.

---

## 🧪 Usage

1. Open the notebook in **VS Code** or **Jupyter Lab**.  
2. Run the cells step-by-step to:
   - Import the required packages.  
   - Load the DDColor model from ModelScope.  
   - Select a sample black-and-white image.  
   - Generate and display the colorized output.

---

## 🖼️ Example

**Input (B/W)** → **Output (Colorized)**

| Black & White | Colorized |
|----------------|------------|
| ![Input](https://raw.githubusercontent.com/cyamahat/Photo-Colorization-DDColor/refs/heads/main/sample_image.png) | ![Output](https://raw.githubusercontent.com/cyamahat/Photo-Colorization-DDColor/refs/heads/main/sample_image_colorized.png) |

*Sample image: [Bardeen, Shockley, and Brattain (1948)](https://en.wikipedia.org/wiki/History_of_the_transistor#/media/File:Bardeen_Shockley_Brattain_1948.JPG)*  
(Used for demonstration under Wikipedia Commons licensing.)

---

## 🧠 Model Reference

**DDColor: Deep Colorization with Detail Decoupling**  
- **Paper**: [https://arxiv.org/abs/2212.11613](https://arxiv.org/abs/2212.11613)  
- **Official Model**: [https://modelscope.cn/models/damo/cv_ddcolor_image-colorization](https://modelscope.cn/models/damo/cv_ddcolor_image-colorization)  
- **Original Repo**: [https://github.com/piddnad/DDColor](https://github.com/piddnad/DDColor)

---

## 💡 Notes

- Tested with **Visual Studio Code 1.105**, **Python 3.12**, and **Jupyter** on **Windows 10**.  
- GPU acceleration is optional — CPU works fine for small images (slower).  
- ModelScope automatically downloads the DDColor model on first use.

---

## 🪪 License

This project follows the same license as DDColor.  
Sample image © Wikipedia / Wikimedia Commons.

---

## 🤝 Acknowledgements

- DDColor implementation by [piddnad/DDColor](https://github.com/piddnad/DDColor)  
- Model provided by [ModelScope](https://modelscope.cn/models/damo/cv_ddcolor_image-colorization)
- Sample image from Wikipedia: *[John Bardeen, William Shockley and Walter Brattain at Bell Labs, 1948](https://en.wikipedia.org/wiki/History_of_the_transistor#/media/File:Bardeen_Shockley_Brattain_1948.JPG)*  

