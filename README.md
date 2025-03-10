# Single Image Dehazing using Pix2Pix GAN

**Overview**<br>
This project implements an advanced **single-image dehazing** method using the **Pix2Pix conditional Generative Adversarial Network (cGAN)**. The primary goal is to effectively remove haze from images, enhancing visibility and preserving structural details.

**Key Features**<br>
- Utilizes **Pix2Pix conditional GAN (cGAN)**<br>
- Employs a **U-Net-based generator** with encoder-decoder architecture<br>
- Includes **skip connections** to retain fine image details<br>
- Uses a **PatchGAN discriminator** for local realism<br>
- Trained with combined **adversarial loss and L1 loss**

**Technologies Used**<br>
- **Python**<br>
- **PyTorch**<br>
- **Albumentations** for preprocessing<br>
- **Adam optimizer**

**Results**<br>
The proposed approach significantly reduces haze, improving visual clarity and preserving image details. Experimental evaluation demonstrates the model's effectiveness in generating realistic dehazed images.

**Applications**<br>
- Autonomous driving systems<br>
- Surveillance systems<br>
- Remote sensing and related computer vision tasks affected by atmospheric haze

**Future Work**<br>
- Optimization for real-time applications<br>
- Integration of advanced attention mechanisms<br>
- Evaluation on diverse datasets for broader applicability
