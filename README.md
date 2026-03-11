# Smart-PDF-Bleaching-Fix-Yellowing-Stains-and-Scan-Shadows-with-Python
# Converting PDFs to Grayscale

### 🚀 Get Started

### Click the button below to access the notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bQsBrXfAhdH8h_gw53sRLqKcIFrVER2e)

> **IMPORTANT:** Once the notebook opens, go to **File > Save a copy in Drive**. If you do not save a copy, your progress and changes will not be saved to your personal account.

---

📖 What We Are Covering

* **Environment Setup:** You’ll learn to "mount" Google Drive to Google Colab, building a bridge that allows the cloud-based Python environment to access your stored PDF files.

* **The PDF Engine"** The lecture introduces PyMuPDF (fitz), the core tool used to open documents, target specific pages via zero-indexing (where doc[0] is page one), and measure page dimensions.

* **High-Resolution Rendering:** You will convert mathematical PDF data into a visual Pixmap at 300 DPI, the professional standard that ensures text remains sharp and clear for further processing.

* **Grayscale Optimization:** The guide explains why collapsing three color channels (RGB) into one (Luminance) reduces the data workload by 66%, making background removal faster and more accurate.

* **Data Reshaping with NumPy:** You’ll use NumPy to transform a flat list of raw pixel numbers into a structured 2D Matrix (height and width), which OpenCV then uses to save the final image file.

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
