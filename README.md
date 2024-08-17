# U-Net for Cardiac MRI Segmentation

This project was completed as part of the IMA206: Computational Photography / Patch Methods course at Télécom Paris.

## Project Description

This project implements a U-Net architecture for the segmentation of 3D cardiac MRI images, focusing on the left ventricle, right ventricle, and myocardium. The goal is to achieve accurate anatomical segmentation, which is a crucial step in computer-aided diagnosis of cardiac conditions.

## Dataset

The project uses the ACDC (Automated Cardiac Diagnosis Challenge) dataset. This dataset contains cardiac MRI images along with expert annotations for segmentation.

Dataset link: [ACDC Challenge](https://www.creatis.insa-lyon.fr/Challenge/acdc/)

## Methodology

1. Data Preprocessing: Preparation of 3D MRI images for input into the U-Net model.
2. U-Net Implementation: Using PyTorch and Monai to build and train the U-Net architecture.
3. Training: Utilizing the ACDC dataset to train the model.
4. Evaluation: Assessing the model's performance using appropriate metrics.
5. Visualization: Creating visual representations of the segmentation results.

## Future Directions

Depending on time and interest, the project could be extended in several directions:

1. Computer-aided diagnosis of cardiac pathologies
2. Generalization to multicentric, multivendor, multi-disease data using various augmentations and test-time augmentations
3. Self-supervised pretraining of segmentation models from raw, unlabeled data for improved few-shot segmentation

## References

1. Bernard, Olivier, et al. "Deep learning techniques for automatic MRI cardiac multi-structures segmentation and diagnosis: is the problem solved?." IEEE transactions on medical imaging (2018).
2. Ronneberger, O., Fischer, P., & Brox, T. (2015, October). "U-net: Convolutional networks for biomedical image segmentation." In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.
3. Campello, V. M., Gkontra, P., Izquierdo, C., Martin-Isla, C., Sojoudi, A., Full, P. M., ... & Lekadir, K. (2021). "Multi-centre, multi-vendor and multi-disease cardiac segmentation: the M&Ms challenge." IEEE Transactions on Medical Imaging, 40(12), 3543-3554.

## Acknowledgements

Project Supervisor: Loïc le Folgoc