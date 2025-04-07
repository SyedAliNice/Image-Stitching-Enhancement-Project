
# 📸 Image Stitching & Enhancement Project
![image alt]()

#   🔍 Overview

This project focuses on combining multiple aerial images into a single panoramic image and enhancing image quality using a deep learning model known as SwinIR (Swin Transformer for Image Restoration). The objective is to improve visibility and continuity in drone-captured aerial images for analysis and presentation.
#   📂 Project Structure

-   Image_stiching&enhancement.ipynb: Contains the full pipeline for stitching and enhancing images.

-   network_swinir.py: Defines the SwinIR model architecture.

-   cropped_image.jpg: A cropped sample image used in the process.

-   enhanced_image (2).jpg: Example of an enhanced image.

-   Image_Stitching_Report.docx: Detailed explanation and results of the project
#   ⚒️ Features

✅ Image Stitching

-   Utilizes OpenCV's cv2.Stitcher_create() and manual homography-based approaches.

-   Detects and matches features across overlapping images.

-   Computes transformation matrices to align and stitch images seamlessly.

-   Outputs panoramic views with corrected alignment.

✅ Image Enhancement (Super-Resolution)

-   Uses the SwinIR model to enhance low-resolution or stitched images.

-   Applies transformer-based attention for high-quality restoration.

-   Improves texture and structural detail.

#   🧪 Technologies Used

-   Python

-   OpenCV

-   PyTorch

-   NumPy

-   Matplotlib

-   SwinIR (Swin Transformer)
#   🧰 Installation & Usage

**Step 1: Clone the Repository**

    git clone https://github.com/your-username/image-stitching-enhancement.git
    cd image-stitching-enhancement
**Step 2: Install Dependencies**

    pip install -r requirements.txt
**Or install manually:**

    pip install opencv-python torch torchvision matplotlib numpy
**Step 3: Run the Notebook**

    jupyter notebook Image_stiching&enhancement.ipynb
#   🧠 SwinIR Model Overview
-   **Architecture:** Combines Swin Transformer blocks with residual learning.

-   **Purpose:** Enhances resolution, removes blur, and reconstructs textures.

-   **File:** network_swinir.py contains the full model definition and configuration.    

#   📄 Report Summary
-   Discusses different stitching approaches and their accuracy.

-   Compares raw vs. enhanced outputs.

-   Includes visual examples of improvements.

-   Evaluation metrics include PSNR and SSIM (if computed).
#   📷 Example Outputs

-   Side-by-side comparisons of original vs. stitched vs. enhanced images.

-   Clear visuals of transformations and detail restoration.
#   🤝 Acknowledgments

-   SwinIR paper and GitHub repository: https://github.com/JingyunLiang/SwinIR

-   OpenCV for image stitching techniques.

-   PyTorch community for model training and deployment tools.
