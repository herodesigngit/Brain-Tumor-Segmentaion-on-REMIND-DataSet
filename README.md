This project aims to perform automatic segmentation of brain tumors from **MRI** images using deep learning. The model uses a 3D **U-Net** architecture, which is effective for image segmentation tasks. The **REMIND Dataset** is used for training and evaluation.

### Key Features:
- **MRI brain tumor segmentation**.
- **U-Net architecture** adapted for tumor detection and segmentation.
- **Segmentation Masks**: The model generates binary masks indicating tumor regions.
- **Evaluation Metrics**: Dice Coefficient, IoU (Intersection over Union), and accuracy.

The model is trained on the REMIND Dataset, which is a publicly available dataset for brain tumor segmentation. The dataset contains MRI images of the brain, along with corresponding segmentation masks for tumor regions.

You can download the dataset from the official repository or https://www.cancerimagingarchive.net/collection/remind/
The Brain Resection Multimodal Imaging Database (ReMIND) contains pre- and intra-operative data collected on 114 consecutive patients who were surgically treated with image-guided tumor resection between 2018 and 2022. For all patients, preoperative MRI, 3D intraoperative ultrasound series, and intraoperative MRI are available. Additionally, each case typically contains segmentations, including the preoperative tumor, the pre-resection cerebrum, the previous resection cavity derived from the preoperative MRI (if applicable), and any residual tumor identified on the intraoperative MRI. In total, this collection contains 369 preoperative MRI series, 320 3D intraoperative ultrasound series, 301 intraoperative MRI series, and 356 segmentations. We expect this data to be a resource for computational research in brain shift and image analysis as well as for neurosurgical training in the interpretation of intraoperative ultrasound and intraoperative MRI.
