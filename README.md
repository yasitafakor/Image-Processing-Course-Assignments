# Image-Processing-Course-Assignments

### Overview
This repository showcases a series of image processing projects, each focusing on key techniques and methods for enhancing, analyzing, and modifying digital images. The projects cover various aspects of image processing, from basic transformations to advanced filtering and segmentation techniques. Below is a summary of the important concepts and techniques used in each project.

### Projects

#### 1. **Point Intensity Transformations and Histogram Analysis**
   - **Techniques Used:**
     - **Point Intensity Transformations:** Modifying image quality through pixel-by-pixel adjustments, including brightness, contrast, and color correction.
     - **Histogram Analysis:** Drawing and analyzing histograms for both grayscale and color images to assess brightness contrast and dynamic range.
     - **Histogram Stretching and Equalization:** Improving visual quality by adjusting intensity distributions and enhancing contrast through histogram manipulation.

#### 2. **Contrast Enhancement Techniques**
   - **Techniques Used:**
     - **Linear Transformation Functions:** Applying linear functions to increase image contrast, enhancing visibility of details in both dark and light areas.
     - **Image Negatives Conversion:** Adjusting negative images to more suitable representations using linear transformations.

#### 3. **Logarithmic Intensity Transformation and Histogram Manipulation**
   - **Techniques Used:**
     - **Logarithmic Transformation:** Enhancing details in darker regions of an image to improve contrast in low-intensity areas.
     - **Histogram Stretching and Equalization:** Implementing methods to extend the range of intensity values and uniformly distribute them across the image to improve overall contrast.

#### 4. **Image Filtering and Edge Detection**
   - **Techniques Used:**
     - **Linear and Non-linear Filtering:** Applying filters such as average, Gaussian, and median filters to smooth images and reduce noise.
     - **Edge Detection:** Using the Sobel filter to detect edges and identify intensity changes in horizontal and vertical directions.
     - **Combination of Techniques:** Evaluating the effectiveness of combining edge detection with contrast enhancement techniques for optimized image analysis.

#### 5. **Image Segmentation and Interpolation Techniques**
   - **Region Growing Segmentation:**
     - **Techniques Used:**
       - **Seed Selection:** Manually or automatically selecting seed points for segmenting specific regions (e.g., white and gray matter in brain scans).
       - **Region Growing:** Expanding regions by adding neighboring pixels that meet similarity criteria, using both constant and variable thresholds.
     - **Implementation:** Converting images to grayscale, selecting seed points, applying region growing, and analyzing results.
   - **Interpolation Techniques:**
     - **Techniques Used:**
       - **Nearest Neighbor:** Simplistic method selecting the closest pixel value.
       - **Bilinear Interpolation:** Considering the 2x2 neighborhood for smoother results.
       - **Bicubic Interpolation:** Using a 4x4 neighborhood for even smoother results.
     - **Analysis:** Comparing image quality and processing time across different interpolation methods.

#### 6. **Image Compression and Format Comparison**
   - **Techniques Used:**
     - **Compression Techniques:** Understanding lossy (JPEG) vs. lossless (PNG) compression, and working with formats like BMP, TIFF, and GIF.
     - **Comparing Formats:** Analyzing trade-offs between image quality and file size, combining multiple images into a single file, and creating GIFs from JPEGs.
     - **Downsampling:** Exploring methods to reduce pixel count and achieve compression while maintaining visual quality.

#### 7. **Image Processing for Document Analysis**
   - **Techniques Used:**
     - **Character Detection:** Processing text documents to identify and highlight characters, essential for optical character recognition (OCR).

#### 8. **Image Resolution and DPI Calculation**
   - **Techniques Used:**
     - **Resolution Calculation:** Determining the required resolution for specific dimensions in metric and imperial units.
     - **DPI Calculation:** Converting resolution into DPI for printing and display quality.

#### 9. **Image Conversion and Thresholding**
   - **Techniques Used:**
     - **Grayscale and Binary Conversion:** Simplifying images to single-channel or binary formats for further processing.
     - **Custom Thresholding:** Dividing pixel intensity ranges into categories and assigning representative values for each category.

#### 10. **Image Resizing and Histogram Analysis**
   - **Techniques Used:**
     - **Scaling Images:** Resizing images while preserving or altering aspect ratio.
     - **Histogram Representation:** Visualizing and comparing histograms for different image types to enhance contrast and quality.

#### 11. **Image Loading, Display, and Manipulation**
   - **Techniques Used:**
     - **Loading and Displaying Images:** Understanding RGB and BGR formats.
     - **Pixel Manipulation:** Accessing and modifying pixel values.
     - **Region of Interest (ROI) Selection:** Selecting and manipulating specific image regions.
     - **Channel Splitting and Merging:** Working with color channels and performing arithmetic operations.
     - **Image Rotation:** Implementing custom rotation based on trigonometric transformations.
     - **Contrast and Brightness Adjustment:** Enhancing visual quality by adjusting contrast and brightness.
