## 1. Region Growing Segmentation

In this project, I implemented region growing segmentation to isolate specific regions such as white and gray matter in brain scans.

### Steps I Followed:

1. **Seed Selection:**
   - I manually selected seed points from the image.
   - As an alternative, I implemented automatic seed point selection.

2. **Similarity Criterion:**
   - I defined criteria to determine pixel similarity, which helped in grouping pixels into regions.

3. **Region Formation:**
   - Started the region growing process from the seed point, expanding the region by including neighboring pixels that matched the seed’s characteristics.

4. **Region Expansion:**
   - Continued expanding the region until no additional pixels could be added.

5. **Repeating the Process:**
   - The segmentation was iteratively applied until convergence.

### Practical Implementation:

1. **Convert Image to Grayscale:**
   - Converted the provided `Color_MRI.png` image to grayscale.

2. **Seed Selection:**
   - Manually selected seed points from both white and gray matter regions.

3. **Region Growing Function:**
   - Implemented a `region growing` function with:
     - **Threshold Difference:** To determine how different a pixel could be from the seed point.
     - **Threshold Type:**
       - **Constant Threshold:** Used the intensity at the seed point.
       - **Variable Threshold:** Adjusted based on the average intensity of the region.

4. **Region Growing Process:**
   - The function was applied iteratively using the defined threshold types.

5. **Output and Analysis:**
   - Displayed the number of iterations needed.
   - Presented both original and segmented images.
   - Analyzed the results to understand how different thresholds affected segmentation.

## 2. Interpolation Techniques

In this project, I explored different interpolation methods for resizing images and evaluated their impact on image quality.

### Interpolation Methods:

1. **Nearest Neighbor:**
   - Used this simplest method, which selects the nearest pixel’s value.

2. **Bilinear Interpolation:**
   - This method considered the closest 2x2 neighborhood of known pixels.

3. **Bicubic Interpolation:**
   - Applied bicubic interpolation, which considers a 4x4 neighborhood, providing smoother results.
