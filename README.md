# Smart-PDF-Bleaching-Fix-Yellowing-Stains-and-Scan-Shadows-with-Python
# Converting PDFs to Grayscale

### 🚀 Get Started

### Click the button below to access the notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bQsBrXfAhdH8h_gw53sRLqKcIFrVER2e)

> **IMPORTANT:** Once the notebook opens, go to **File > Save a copy in Drive**. If you do not save a copy, your progress and changes will not be saved to your personal account.

---

📖 What We Are Covering

* **Environment Integration:** Connects Google Colab to Google Drive, creating a persistent data bridge for cloud-based file management.
* **PDF Engine Initialization:** Installs and imports the PyMuPDF (fitz) library to handle PDF parsing, page extraction (using zero-indexing), and coordinate mapping.
* **High-Fidelity Rendering:** Converts mathematical PDF instructions into a 300 DPI Pixmap, ensuring the resolution is sharp enough for accurate text preservation and background cleaning.
* **Grayscale Transformation:** Collapses 3-channel RGB data into a single Luminance channel, reducing the computational memory footprint by 66% and simplifying noise filtering.
* **Data Reshaping with NumPy:** Utilizes NumPy to transform raw pixel buffers into structured 2D Grayscale Matrices that are compatible with OpenCV for final image export and analysis.

---

### 🛠 Prerequisites
* A Google Account (to use Colab).
* (Optional) Any specific files used in this notebook are hosted in this repository and will be loaded automatically via the code cells.

---

### ⚖️ Intellectual Property & Terms of Use
**Personal Use Only:**
This material is provided exclusively for students of **TrainDoc AI**.

Link https://traindocai.com/

**Attribution:**
Parts of this code and educational content are adapted from the course **"Smart PDF Bleaching: Fix Yellowing, Stains, and Scan Shadows with Python"** by **TrainDoc AI**. All original rights to that content belong to the respective copyright holders.

Link https://traindocai.com/courses-page/smart-pdf-bleaching-fix-yellowing-stains-and-scan-shadows-with-python/

**Restrictions:**
* **No Redistribution:** You may not redistribute, republish, or sell any part of this notebook.
* **No Public Posting:** Please do not post solutions or modified versions of this notebook to public websites or other repositories.
* **All Rights Reserved:** Except where original course copyrights apply, the modifications and instructional text are copyright © 2026 TrainDoc AI.
