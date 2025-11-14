# Comparative-Study-of-Edge-Detection-After-Denoising-in-Medical-Image-Processing

# Abstract

Medical images provide critical details necessary for accurate diagnosis and treatment. However, speckle noise often leads to poor edge representation, losing important structural information. In this paper, we evaluate the performance of five edge detection methods—Canny, ISEF, Marr–Hildreth, Kirsch compass, and Scharr—on the MIEDT dataset. Additionally, we apply three denoising filters—OSRAD, Lee,  Median Guided DWT—to reduce speckle noise. The edge detection techniques are then reapplied to evaluate edge preservation and clarity enhancements following denoising. Python libraries like scikit-image, OpenCV, and PyWavelets are used to implement all of the techniques. The following performance metrics are used for evaluation: precision, recall, F1-score, intersection over union (IoU), peak signal-to-noise ratio (PSNR), structural similarity index (SSIM), signal-to-noise ratio (SNR), and mismatch percentage.

# Methodology

<img width="692" height="334" alt="image" src="https://github.com/user-attachments/assets/72c2adf9-4c9a-4a8c-9ea4-ff875d2c73fc" />

# Results

<img width="1098" height="686" alt="image" src="https://github.com/user-attachments/assets/eaca96dd-9d1c-4212-bcae-33b715c4f16b" />

<img width="1340" height="624" alt="image" src="https://github.com/user-attachments/assets/96be4574-89b3-4dad-9066-05c066a847cd" />

# Conclusion
OSRAD + Canny consistently outperformed other methods across all key metrics:Precision, Recall, F1-Score, SSIM→ Indicates excellent edge preservation and structural clarity.
PSNR and SNR values were highest for OSRAD + Canny, confirming strong noise suppression with minimal distortion.
Lee Filter: Achieved a good trade-off between smoothing and edge retention.
Median Filter: Effective in removing impulsive noise and enhancing edges.
In contrast, Marr–Hildreth and Kirsch detectors underperformed, particularly in low-contrast areas, due to noise sensitivity and directional bias.
Overall, the experimental findings affirm that selecting an optimal pair of denoising and edge detection techniques is crucial for enhancing diagnostic image quality in medical imaging applications.



