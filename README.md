# Object-Height-Estimator
The system calculates the height of an object from a 2D image by analyzing the object's shadow. By leveraging geometric principles and the relationship between the object and its shadow, it accurately estimates the height, providing a reliable solution for applications where direct measurement is challenging or impractical. This approach is particularly useful in fields like computer vision, remote sensing, and augmented reality.

* Grayscale Conversion
The 2D image is converted into grayscale to simplify the data and enhance processing efficiency.

* Binary Transformation
The grayscale image is further processed into a binary format to isolate the object's shadow from the background.

* Shadow Localization
A bounding rectangle is formed around the detected shadow to define its dimensions and spatial boundaries.

* Sun Angle Calculation
Using the geographical coordinates (latitude and longitude) of the image location, the system calculates the sun's angle at the time the photo was captured.

* Height Estimation
By applying geometric principles and analyzing the relationship between the shadow's dimensions and the sun's angle, the system computes the height of the object with high precision.
