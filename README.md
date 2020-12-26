# Cartoon-Image
Covert real image into cartoon Format
## Steps
- 1.Apply a bilateral filter to reduce the color palette of the image.
- 2.Convert original color image into grayscale image.
- 3.Apply median blur to reduce image noise in the resultant grayscale image.
- 4.Create an edge mask from the grayscale image using adaptive thresholding.
- 5.Combine the color image from step 1 eith edge mask from step 4.

## Libraries
- cv2
- numpy 
