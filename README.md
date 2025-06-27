# Multi-Organ Segmentation from CT/MRI Images

This project focuses on the segmentation of abdominal organs using deep learning techniques on medical imaging data (CT or MRI). The segmentation results help identify various organs from input scans, which is vital for medical diagnosis, surgical planning, and disease monitoring.

## 📌 Project Highlights

- **Input**: CT or MRI axial slices.
- **Output**: Pixel-wise organ segmentation for multiple organs.
- **Model**: Deep learning model (e.g., U-Net and swin transformer).
- **Evaluation**: Comparison between predicted segmentation and ground truth using color-coded masks.

## 🖼️ Sample Output

![Segmentation Output](output.png)

- **Left**: Original CT/MRI image.
- **Center**: Ground truth segmentation.
- **Right**: Predicted segmentation by the model.
- A color-coded legend identifies organs like spleen, kidneys, liver, pancreas, etc.

## 🧠 Organs Segmented

- Spleen
- Gallbladder
- Stomach
- Right Kidney
- Left Kidney
- Liver
- Esophagus
- Aorta
- IVC (Inferior Vena Cava)
- Pancreas
- Veins
- Right Adrenal
- Left Adrenal

## 🧪 Requirements

Install the following libraries before running the notebook:
pip install numpy matplotlib opencv-python tensorflow

phase4_2.ipynb: Jupyter notebook for training, testing, and visualizing the segmentation results.

🚀 How to Run
Load and preprocess the dataset.

Train or load the trained model.

Run the phase4_2.ipynb notebook.

Observe the predictions vs ground truth for validation images.

![output](https://github.com/user-attachments/assets/eb53bd8c-8ccb-49c9-b0e4-30d9ddeb3242)
