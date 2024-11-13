# Realsese Edge detection
# Requisite
my encironment
Opencv 3.4.0
realsense SDK 2.55.1   d455


#run

mkdir build
cd build
cmake ..
make 

C++ implementation of Pin detection algorithms.

Currently available algorithms:

 - Enhance lightness (light average value > 14 (set by yourself) )
 - setting ROI (xy direction)
 - Image Binarization & threshold 
 - Image erode & dilate
 - Scharr operator

The project includes GUI for viewing results.

## Examples

### Original image

![](result/original_img.jpg)

### Canny edge detector

![](result/binaryImage1.jpg)

### output pin detection

![](result/output_img.jpg)
