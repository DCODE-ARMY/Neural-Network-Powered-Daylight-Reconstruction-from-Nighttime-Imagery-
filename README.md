# Neural Network-Powered Daylight Reconstruction from Nighttime Imagery

## About This Project

This project explores the use of neural networks to reconstruct daylight scenes from nighttime images. By fusing concepts from **StyleGAN** and **CycleGAN**, a novel architecture has been developed to enable effective **day-night image translation**. The model aims to transform nighttime scenes into realistic daytime images, which can be beneficial for applications like enhanced surveillance, urban planning, and environmental studies.

Despite constrained computational resources, the project achieved significant results, demonstrating the potential of combining **Wasserstein Loss** and **Binary Cross Entropy (BCE)** in training generative adversarial networks for high-quality image translation.

## Key Features
- **Hybrid GAN Architecture**: The model fuses **StyleGAN** and **CycleGAN** to leverage both style transfer capabilities and cyclic consistency.
- **Custom Loss Functions**: Uses a combination of **Wasserstein Loss** and **Binary Cross Entropy** for better stability during training and improved image quality.
- **Day-Night Translation**: Focused on translating nighttime images into realistic daytime scenes.
- **Application Areas**: Useful for improved image analysis in surveillance, environmental research, and image enhancement.

### Dataset Preparation
- **Prepare the Dataset**: The dataset should include paired day and night images of the same scenes. You can use publicly available datasets like **Cityscapes** or create your own dataset with day-night pairs.
- **Data Organization**: Place the dataset in the `data/` folder. The structure should include separate subfolders for **daytime** and **nighttime** images.


## Challenges and Limitations
- **Resource Constraints**: Due to limited computational resources, the model could only achieve partial results. More computational power would allow for further tuning and a more refined model.
- **Training Time**: The hybrid architecture, while powerful, is computationally expensive, requiring extensive GPU resources for effective training.
- **Image Quality**: Achieving high-quality day-night transformations with realistic details remains a challenge, and further refinement is required to achieve optimal results.

## Future Work
- **Model Optimization**: Optimize the model architecture to improve performance with limited resources.
- **Advanced Loss Functions**: Experiment with additional loss functions such as **Perceptual Loss** for further quality improvements.
- **More Data**: Expand the training dataset to include diverse scenes for better generalization.

