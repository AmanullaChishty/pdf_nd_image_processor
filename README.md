# 🔧 PDF & Image Processor

A sleek, privacy-first **browser-based** tool to compress, convert, and optimize PDFs and images **entirely client-side**. Your files never leave your device—no uploads, no servers.

🔗 **Live Demo**: [amanullachishty.github.io/pdf_nd_image_processor](https://amanullachishty.github.io/pdf_nd_image_processor/)

---

## 🌟 Features

- **PDF Compression**  
  - Define target size (KB) and quality level  
  - Progressive compression with live progress bar  
  - Feedback on final size reduction

- **PDF → Image Conversion**  
  - Export each page as PNG, JPEG, or WebP  
  - Choose resolution (72, 150, 300 DPI)  
  - Thumbnail previews + download

- **Image → PDF Conversion**  
  - Batch-convert multiple images to a single PDF  
  - Select page size (A4, Letter, Legal, or custom)  
  - Adjustable output image quality

- **Image Compression**  
  - Set target size (KB) and quality (range slider)  
  - Automatic quality adjustment to meet your target  
  - Preview result + download option

- **Great UX**  
  - Drag‑and‑drop and click‑to-upload  
  - Responsive, dark‑mode ready UI  
  - Real-time progress indicators

---

## 🧩 Tech Stack

- **HTML**, **CSS** (custom styling + responsive design)  
- **JS Libraries**:
  - `jsPDF` for PDF creation & compression  
  - `pdf.js` for rendering PDF pages  
  - `pdf-lib` for image embedding in PDFs  
- **Pure JavaScript**—no build tools, no backend  
- **Deployed via** GitHub Pages

---

## 🖥️ How to Use Locally

```bash
git clone https://github.com/amanullachishty/pdf_nd_image_processor.git
cd pdf_nd_image_processor
open index.html  # or serve with any static host
