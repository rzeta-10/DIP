# Python Code to Compare Degraded and Original Face Image Quality

The following Python code performs the following steps:
1. **Degrade the image**:
   - Blur the image.
   - Add Gaussian noise.
   - Compress and decompress the image using JPEG 2000 at a quality level of 70%-80%.
2. **Calculate the quality**:
   - Compare the degraded image with the original image without using the built-in PSNR function.