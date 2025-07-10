# Kaggle-RSNA-2022-Cervical-Spine-Fracture-Detection
Kaggle Competition: [RSNA 2022 Cervical Spine Fracture Detection] https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection
Cervical spine fracture detection using U-Net for vertebrae segmentation and Faster R-CNN for fracture detection.

## Project Overview
This project addresses the Kaggle competition task of detecting cervical spine fractures in 3D CT scans. The solution involves:
1. **Data Preprocessing**: Conversion of NIfTI/DICOM files to binary masks and region isolation.
2. **Vertebrae Segmentation**: U-Net model (PyTorch) with transfer learning to segment cervical vertebrae (~70% IoU).
3. **Fracture Detection**: Faster R-CNN trained on dilated masks for bounding box regression.

## Screenshots
Sample of U-Net vertebrae mask predictions:
<img width="974" height="655" alt="Image" src="https://github.com/user-attachments/assets/e80f8fa6-9e6f-4653-b2d9-a1898d3c42e9" />
