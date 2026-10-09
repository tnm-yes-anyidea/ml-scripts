# Open-Source PDF-to-LaTeX Math OCR Project Matrix

Below is a curated directory of open-source projects, specialized models, and document parsing frameworks optimized for converting PDFs of handwritten or mixed-media mathematical pages into clean, structured LaTeX.

---

## 1. End-to-End PDF Translation Frameworks & Tools
These are complete software repositories designed to take multi-page inputs (PDFs or batches of images) and output structural markdown/LaTeX documents.

| Project Name | Primary Focus | Best Used For | Repository / Ecosystem Link |
| :--- | :--- | :--- | :--- |
| **`notes2latex`** | Multi-page notes to LaTeX | Smart conversion with self-correcting LaTeX compilation loops. | [GitHub - notes2latex](https://github.com/ "notes2latex github") |
| **`Pix2Text` (P2T)** | Mixed layout text & math OCR | Automatically segments images/PDF pages into structural text vs. formula zones. | [GitHub - Pix2Text](https://github.com/breezedeus/Pix2Text "Pix2Text github") |
| **`Marker`** | Full PDF document conversion | Converts arbitrary PDFs to Markdown/LaTeX with high speed and structural fidelity. | [GitHub - Marker](https://github.com/VikParuchuri/marker "Marker github") |
| **`LaTeX-OCR` (Pix2Tex)** | Formula image to LaTeX | The gold standard CLI/GUI tool for cropping and instantly parsing complex math. | [GitHub - LaTeX-OCR](https://github.com/lukas-blecher/LaTeX-OCR "LaTeX-OCR github") |

---

## 2. Specialized Multi-Page & Multi-Modal Document Parsers
These tools extract underlying text and equations natively from PDFs while retaining geometric layout context.

*   **`texify`**: Developed by the creator of Marker, this lightweight tool maps document screenshots and math images directly to clean markdown equations.
*   **`Nougat` (Neural Optical Understanding for Academic Documents)**: Meta AI's transformer-based pipeline that reads PDF pages as images and prints out operational LaTeX code, ideal for dense academic layouts.

---

## 3. Tiny Frontier Multimodal & VLM Backends
If you prefer building a custom processing script over raw PDF pages, these small-footprint vision models understand handwritten spatial relationships better than traditional OCR engines.

*   **`Qwen2.5-VL-7B` / `Qwen2-VL-7B`**: Leading open-source multimodal architectures for multi-page visual document parsing and mathematical text translation.
*   **`Llama-3.2-Vision-11B`**: A highly efficient, edge-deployable vision-language model tailored for structured page interpretation and text synthesis.
*   **`TrOCR` Fine-tunes (e.g., `tjoab/latex_finetuned`)**: Super-lightweight math-writing weights (< 1B parameters) ideal for local execution on standard consumer processors.
