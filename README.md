# Shoe Brand Classification

**COMPS492F / COMP3920SEF Machine Learning Project**

A deep learning model that classifies images of three shoe brands – **Nike, Adidas, Converse** – with **86.7% validation accuracy** (best observed 90%).

## Team
- Ashwin-Sundar (Student ID: 13139477 )
- Anthony Jesu Ashok Savitha, Maria Dharshini (Student ID: 13126390)

## Project Overview
- **Task:** 3‑class image classification (240×240 RGB)
- **Dataset:** 200 training images per class, 30 validation images per class
- **Model:** EfficientNet‑B0 with transfer learning and custom classification head
- **Accuracy:** 88.89% on validation set (far above the 50% baseline)

## Files
| File | Description |
|------|-------------|
| `Mini_Project-2.ipynb` | Final Colab notebook (data prep, training, evaluation) |
| `shoe_classifier_model.keras` | Trained model (~20 MB) |
| `report.pdf` | Project report (2‑3 pages) |

## How to Run
1. Open the notebook in Google Colab (or Jupyter)
2. Mount your Google Drive and place the dataset in the specified structure
3. Run all cells – training will start automatically
4. The model will be saved as `shoe_classifier_model.keras`

## Libraries Used
Python, TensorFlow/Keras, NumPy, Matplotlib, Scikit‑learn, Seaborn

## Results
- Best validation accuracy: **88.89%**
- Training accuracy: ~95%
- Model size: ~20 MB (well within 100 MB limit)
