# Processing the Colour Lena Image

### 1. Download and Process the Color Lena Image
   - Load the color Lena image (`fc`).
   - Convert it to grayscale (`fg`) using:
     - Averaging of R, G, B channels (manual method).
     - Built-in function for grayscale conversion.
   - Display both grayscale images to check for differences.

### 2. Resize the Grayscale Image (`fg`) by a Factor of 2
   - Resize using:
     - **Nearest Neighbor Interpolation**:
       - Manual implementation (without built-in function).
       - Using a built-in function.
     - **Bi-linear Interpolation**:
       - Manual implementation (without built-in function).
       - Using a built-in function.
     - **Bi-cubic Interpolation**:
       - Using a built-in function.