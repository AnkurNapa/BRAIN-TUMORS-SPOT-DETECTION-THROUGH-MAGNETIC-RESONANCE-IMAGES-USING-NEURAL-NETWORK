# BRAIN-TUMORS-SPOT-DETECTION-THROUGH-MAGNETIC-RESONANCE-IMAGES-USING-NEURAL-NETWORK
![image](https://github.com/AnkurNapa/BRAIN-TUMORS-SPOT-DETECTION-THROUGH-MAGNETIC-RESONANCE-IMAGES-USING-NEURAL-NETWORK/assets/52191181/a17411e3-f4f5-41f1-a757-260712636db4)


## Overview
This project aims to identify and segment brain tumors from magnetic resonance imaging (MRI) scans using advanced neural network methodologies. The primary focus is on using deep learning techniques for medical imaging, contributing to faster and more accurate diagnosis, thereby facilitating timely treatment for patients.

## Dataset
The dataset used in this project is available on Kaggle and can be found at the following link: [BraTS20 Dataset Training Validation](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation). This dataset includes a rich collection of MRI scans showcasing various cases, providing a robust foundation for developing and testing our neural network models.

## Methodologies
This project employs two main deep learning architectures, known for their effectiveness in image segmentation tasks, particularly in the medical imaging domain:

### 1. U-Net
U-Net is renowned for its efficiency in biomedical image segmentation, credited to its unique architecture optimized for detailed delineation in images. The model's 'U-shaped' structure, expansive path, and contracting path contribute to its precision and effectiveness in segmenting complex images with fewer training samples. The detailed methodology and architecture are discussed in the [`U-NET final.ipynb`](U-NET%20final.ipynb) Jupyter notebook.

### 2. DeepLabV3+
DeepLabV3+ extends the capabilities of convolutional neural networks for semantic image segmentation. This model captures intricate details and larger contextual information, essential for tasks like identifying tumor boundaries in MRI scans. The architecture incorporates features like Atrous Spatial Pyramid Pooling (ASPP) and encoder-decoder structure, which allow it to perform precise segmentation. The comprehensive details of its implementation are available in the [`mri-brain-tumor-segmentation-using-deeplabv3.ipynb`](mri-brain-tumor-segmentation-using-deeplabv3.ipynb) and [`DeepLabV3+ final.ipynb`](DeepLabV3+%20final.ipynb) notebooks.

## Files Description
- Contains the exploratory data analysis performed on the MRI scans, offering insights into the data's characteristics and challenges.
- [`U-NET final.ipynb`](U-NET%20final.ipynb): Details the U-Net model architecture, training process, and evaluation on MRI scans for brain tumor segmentation.
- [`mri-brain-tumor-segmentation-using-deeplabv3.ipynb`](mri-brain-tumor-segmentation-using-deeplabv3.ipynb): Describes the process of using the DeepLabV3+ model for brain tumor segmentation in MRI scans.
- [`DeepLabV3+ final.ipynb`](DeepLabV3+%20final.ipynb): An extended discussion on the DeepLabV3+ model, outlining its architecture, training, and performance metrics.

## Installation and Usage
To replicate this study's findings or use the models for new data, follow these steps:

1. Clone the repository to your local machine or download the notebooks and files.
2. Download the dataset from the provided link and extract it in a suitable location.
3. Update the dataset paths in the notebooks to reflect your local setup.
4. Install the necessary Python packages and dependencies using the `requirements.txt` file included in the repository. You can use the command `pip install -r requirements.txt` in your virtual environment to install these dependencies.
5. Open the Jupyter notebooks and execute the cells in sequence, or use an environment like Jupyter Lab to interact with the notebooks.

## Contributing
We welcome contributions to this project, whether they be improvements to the algorithms, enhanced documentation, more efficient code, etc. Please use GitHub issues and Pull Requests to contribute.

Ankur Napa
napankur@gmail.com
Linkedin - https://www.linkedin.com/in/ankur-napa/

## Acknowledgments
We extend our sincere gratitude to the researchers and professionals whose studies and papers have provided us with the foundational knowledge and methodologies adapted in this project.

---

By adding the part about `requirements.txt` in the "Installation and Usage" section, users will know they need to install the dependencies listed in the `requirements.txt` file to ensure the project runs smoothly in their environments.
