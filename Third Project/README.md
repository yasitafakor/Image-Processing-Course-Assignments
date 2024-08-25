### 1. **Image Compression Techniques**:
   - **Lossy vs Lossless Compression**: Understanding the differences between these two types of compression. Lossy compression (e.g., JPEG) sacrifices some image quality for a significant reduction in file size, while Lossless compression (e.g., PNG) retains all original image data but with a less significant reduction in file size.
   - **Specific Image Formats**:
     - **PNG**: A lossless compression format that supports alpha transparency, making it ideal for images requiring high-quality and transparent backgrounds.
     - **JPEG**: A lossy compression format widely used for photographs and images where a smaller file size is more critical than perfect quality.
     - **BMP**: An uncompressed format that stores image data as is, leading to large file sizes but straightforward data manipulation.
     - **TIFF**: A versatile format used primarily in professional environments, supporting multiple layers and different color depths, and capable of storing multiple images in a single file.
     - **GIF**: A format supporting simple animations with an 8-bit color depth, making it suitable for images with limited colors, such as icons or simple graphics.

### 2. **Comparing Image Formats**:
   - **Image Quality vs File Size**: A hands-on comparison between PNG and JPEG formats to analyze the trade-offs between image quality and file size.
   - **Combining Multiple Images**: Techniques for storing multiple images in a single file, such as using the TIFF format, which supports multi-page images.

### 3. **Creating GIFs**:
   - **GIF Creation from JPEGs**: Converting a series of JPEG images into a GIF, a process often used for creating simple animations or slide shows from a collection of photos.

### 4. **Downsampling for Image Compression**:
   - **Downsampling Techniques**: Exploring methods to reduce the number of pixels in an image, such as interpolation, pixel averaging, or pixel dropping, to achieve compression while attempting to maintain visual quality. This includes manually implementing downsampling without relying on built-in OpenCV functions.

### 5. **Image Processing for Document Analysis**:
   - **Character Detection and Highlighting**: Processing an image of a text document to identify characters and draw bounding boxes around them, an essential technique in optical character recognition (OCR) and document analysis.
