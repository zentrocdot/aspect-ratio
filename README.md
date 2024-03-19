# README

Especially in photography, it is important to know the aspect ratio of images. It is often desirable to retain the aspect ratio after cropping an image. The tool aspect-ratio calculates the underlying aspect ratio from any given resolution in the x- and y-direction. The aspect ratio is output without a line break. This enables the direct use in other scripts or programs. 

The calculation is done using the greatest common divisor (GCD) of two integer numbers. If the result does not match the input values, this is due to a suitable aspect ratio. Otherwise, the image is not based on a standard aspect ratio. For example, it has already been edited.
