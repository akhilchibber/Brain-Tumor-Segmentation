# Deep Learning based Brain Tumor Segmentation
<p align="center">
  <img src="https://github.com/akhilchibber/Brain-Tumor-Segmentation/blob/main/BRAIN_TUMOR_SEGMENTATION.png?raw=true" alt="earthml Logo">
</p>

Welcome to the Brain Tumor Segmentation Project! This Github Repository is designed for both newcomers and experienced professionals in the field of machine learning. Our aim is to develop a model capable of accurately segmenting brain tumors from MRI scans using deep learning techniques.

## Dataset
We are utilizing the Brain Tumor Segmentation (BraTS2020) dataset from Kaggle (https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation/data). This dataset includes multimodal MRI scans in NIfTI format (.nii.gz), encompassing various volumes:

1. Native (T1)
2. Post-contrast T1-weighted (T1Gd)
3. T2-weighted (T2)
4. T2 Fluid Attenuated Inversion Recovery (T2-FLAIR)

The tumor annotations are categorized into:

1. Necrotic and non-enhancing tumor core (NCR/NET — label 1)
2. Peritumoral edema (ED — label 2)
3. GD-enhancing tumor (ET — label 4)
   
## Objective
Our primary objective is to segment brain tumors by labeling each pixel as "1" for tumor classes (NCR/NET, ED, ET) and "0" otherwise. We plan to employ a 3D U-Net model for automatic segmentation.

## Approach
1. **Data Preparation:** Load, preprocess, and normalize the data, followed by train-test splitting.
2. **Model Building:** Design and configure the 3D U-Net model architecture suitable for our segmentation task.
3. **Model Training and Validation:** Train the 3D U-Net model on the prepared dataset and validate its performance.
4. **Model Evaluation:** Assess model performance using metrics like accuracy, precision, recall, and F1 score.
5. **Results and Visualization:** Compare model predictions with ground truth to visualize performance.

## Getting Started
1. Clone the repository to your local machine or open it in Google Colab.
2. Ensure you have the required libraries installed: `torch`, `numpy`, `pandas`, `matplotlib`, `nibabel`, `scikit-learn`, `seaborn`, `scipy`, `SimpleITK`, `albumentations`.
3. Download the BraTS2020 dataset from Kaggle and adjust the file paths in the notebook accordingly.
4. Run the Jupyter Notebook to train and evaluate the brain tumor segmentation model.
   
## Target Audience
This Github Respository, specifically the Jupyter notebook is structured to be accessible for beginners, providing detailed explanations and a step-by-step approach, while also encompassing advanced techniques for seasoned practitioners. Let's dive into the world of medical imaging and deep learning to make significant strides in healthcare technology!

## Contributing
We welcome contributions to enhance the functionality and efficiency of this script. Feel free to fork, modify, and make pull requests to this repository. To contribute:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request against the `main` branch.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Author: Akhil Chhibber

LinkedIn: https://www.linkedin.com/in/akhilchhibber/
