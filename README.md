# Galaxy Morphology Classification with Deep Learning

This project is part of the **AAI-521 Applied Computer Vision for AI** course in the Applied Artificial Intelligence Program at the University of San Diego (USD).

<img width="1519" height="723" alt="Screenshot 2026-09-17 at 5 15 40 PM" src="https://github.com/user-attachments/assets/ef7a4e2a-4ea3-4f5f-8269-3c9cecce4af0" />

---

## Dataset

The project uses the **Galaxy10 DECals** dataset, which includes:

- **17,736 RGB galaxy images** at **256×256×3** resolution  
- **10 morphology classes**, covering:  
  - Smooth ellipticals  
  - Cigar-shaped galaxies  
  - Edge-on disks (with and without bulges)  
  - Barred spirals  
  - Unbarred tight spirals  
  - Unbarred loose spirals  
  - Disturbed systems  
  - Mergers  

Images originate from the **DECaLS survey**, part of the **DESI Legacy Imaging Surveys**.  
All samples are centered on a single galaxy and provided as uniform, pre-cut tiles.

---

## Project Objective

The objective of this project is to build and evaluate deep-learning models capable of classifying galaxies into ten scientifically defined morphological categories. This work demonstrates how convolutional neural networks and transfer learning can support automated analysis for large astronomical imaging surveys.

---


Results 

<img width="922" height="947" alt="baseline_cnn_confusion_matrix" src="https://github.com/user-attachments/assets/2a5d2b53-9cf0-4100-8d2d-d2dd1f03e491" />



---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Final_Project_Group_6.git
cd Final_Project_Group_6
