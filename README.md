# Image Enhancement

### Why Image Enhancement?
- Improves visual quality for better interpretation.
- Prepares images for tasks like feature extraction, segmentation, or recognition.
- Essential in fields like medical imaging, satellite imagery, and photography.

---
This repository includes the implementation of the above operations to demonstrate their effects on image enhancement.


Image enhancement involves improving the visual quality of an image by applying various operations. These techniques are crucial for better visualization, analysis, or preprocessing for further tasks like computer vision or image processing.

## Operations Performed

### 1. **Brightness and Darkness (Addition)**
- **Description:** Uniformly adds or subtracts a value to each pixel.
- **Effect:** Makes the image lighter or darker, respectively.
- **Example:** 
  - Adding 50 to all pixels increases brightness.
  - Subtracting 50 decreases brightness.

### 2. **Contrast (Multiplication)**
- **Description:** Multiplies pixel values to adjust the difference between light and dark areas.
- **Effect:** Enhances or reduces the distinction between bright and dark regions.
- **Example:**
  - \(15 \times 10 = 150\): High contrast.
  - \(1.5 \times 10 = 15\): Low contrast.

### 3. **Image Thresholding**
- **Description:** Converts an image to binary by setting pixel values below a threshold to 0 and above it to 255.
- **Effect:** Simplifies the image for object detection or segmentation.
- **Example:** Threshold = 128:
  - Pixel < 128 → 0 (black).
  - Pixel >= 128 → 255 (white).

### 4. **Bitwise Operations**
- **Description:** Logical operations (AND, OR, XOR, NOT) applied pixel-wise between two images or an image and a mask.
- **Effect:** Used for masking, blending, or extracting specific regions of an image.

---


