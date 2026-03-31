# citra-digital-4th-meet


1. RGB to Grayscale

Explanation:
RGB images have 3 colors (Red, Green, Blue). In grayscale, the image is converted into **one channel (black and white)**. Each pixel represents **intensity (0–255)** where 0 is black and 255 is white.

2. Grayscale to Binary

Explanation:
Binary image has only **2 values: 0 (black) and 255 (white)**.
We use a **threshold value** (e.g., 128):

* Pixel > 128 → white
* Pixel ≤ 128 → black

#3. Grayscale to M-bit

Explanation:
Grayscale has **256 levels (8-bit)**.
M-bit reduces the number of levels:

* 4-bit → 16 levels
* 3-bit → 8 levels

This process is called **quantization**.

4. Brightness Adjustment**

Explanation:
Brightness changes how **light or dark** an image is.
It is controlled by adding a constant value (**beta**):

* Positive → brighter
* Negative → darker

5. Contrast Adjustment

Explanation:
Contrast changes the **difference between dark and bright areas**.
It is controlled by a scaling factor (**alpha**):

* High contrast → clearer details
* Low contrast → dull image

6. Grayscale to Histogram

Explanation:
A histogram shows the **distribution of pixel intensities** in an image.

* X-axis → intensity (0–255)
* Y-axis → number of pixels


7. Histogram Equalization

Explanation:
Histogram equalization redistributes pixel values to **spread intensity evenly**.
This improves contrast, especially in low-contrast images.

