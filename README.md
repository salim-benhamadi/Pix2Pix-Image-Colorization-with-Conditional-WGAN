# Pix2pix Colorization with WGAN and U-Net :art:

![GitHub](https://img.shields.io/github/license/salimhammadi15/Pix2Pix-Image-Colorization-with-Conditional-WGAN)
![GitHub stars](https://img.shields.io/github/stars/salimhammadi15/Pix2Pix-Image-Colorization-with-Conditional-WGAN?style=social)

The Pix2pix Colorization with WGAN and U-Net project aims to enhance the performance of the Pix2pix model for colorization tasks by incorporating Wasserstein GAN (WGAN) and a U-Net architecture based on residual blocks. This project utilizes a Python notebook (.ipynb) for implementation.

## 📘 Project Overview

Colorization is an important image-to-image translation task, and Pix2pix is a popular model for such tasks. However, the performance of Pix2pix can be further improved for specific applications like colorization. This project introduces two methods to enhance Pix2pix for colorization: using a WGAN architecture and implementing a U-Net with residual blocks.

WGANs employ the Wasserstein distance metric to train the generator and discriminator, leading to a more stable training process and producing realistic results. U-Net is a convolutional neural network (CNN) architecture well-suited for image segmentation tasks. It incorporates skip connections and enables learning of fine details in input images.

Residual blocks, a building block for neural networks, facilitate gradient flow and accelerate convergence by utilizing skip connections within multiple layers.

Combining WGAN with a U-Net architecture based on residual blocks improves the performance of Pix2pix for colorization. It enhances stability, enables better learning of fine details, and produces high-quality colorized images.

## 📂 Repository Structure

The repository contains the following files:

- `Pix2pix_Colorization_WGAN_UNet.ipynb`: This Python notebook serves as the core project file. It includes the implementation of the WGAN and U-Net architectures for Pix2pix colorization. The notebook provides detailed explanations, code comments, and visualizations.

- `data/`: This directory can be used to store training data for the colorization task. It should include input images and their corresponding ground truth colorized images.

- `results/`: This directory will be automatically generated when running the notebook. It stores the colorized output images and any intermediate results or visualizations.

- `README.md`: The README file provides an overview of the project and instructions for running and contributing to it.

## ▶️ Getting Started

To get started with the Pix2pix Colorization with WGAN and U-Net project, follow these steps:

1. Clone the Repository: Begin by cloning this repository to your local machine using the following command:
   ```
   git clone https://github.com/salimhammadi15/Pix2Pix-Image-Colorization-with-Conditional-WGAN.git
   ```

2. Open the Jupyter Notebook: Launch Jupyter Notebook or any other compatible environment and navigate to the cloned repository.

3. Install Dependencies: Ensure that all required dependencies are installed. You can install them using the following command:
   ```
   pip install -r requirements.txt
   ```

4. Prepare Data: If you have your own training data, place it in the `data/` directory. Ensure that you have both the input images and their corresponding ground truth colorized images.

5. Run the Notebook: Open the `Pix2pix_Colorization_WGAN_UNet.ipynb` notebook and run the cells sequentially. The notebook provides step-by-step instructions for implementing the WGAN and U-Net architectures and training the colorization model.

6. Explore Results: Once the notebook is running, you can visualize the colorized output images and explore the results. The `results/` directory

## 🤝 Contributing

Contributions are welcome to enhance the Solar-Panels-Segmentation-U-Net project. To contribute, follow these steps:

1. Fork the Repository: Click on the "Fork" button at the top right corner of the repository page. This will create a copy of the repository in your GitHub account.

2. Make Changes: Create a new branch, make your desired changes in the notebook, and add any additional features or improvements.

3. Test Your Changes: Run the notebook and ensure that your modifications work correctly.

4. Commit and Push: Commit your changes and push them to your forked repository:
   ```
   git add .
   git commit -m "Your commit message"
   git push origin your-branch-name
   ```

5. Create a Pull Request: Go to the original repository on GitHub and click on the "New Pull Request" button. Fill out the details and submit the pull request. Your changes will be reviewed by the project maintainers.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## 🙏 Acknowledgments

Special thanks to the developers and researchers in the field of Deep learning and GAN for their contributions and inspiration in the implementation of the Pix2Pix Image Colorization with Conditional WGAN.
