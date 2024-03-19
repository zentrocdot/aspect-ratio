# README

<p align="justify">Especially in photography, it is important to know the aspect ratio of images. It is often desirable to retain the aspect ratio after cropping an image. Some graphic tools allow to keep the aspect ratio while cropping an image other not.</p>

<p align="justify">While dealing with old photos from a digital camera I figured out, that the resolution of digital cameras can vary in a wide range.</p>
  
<p align="justify">The tool aspect-ratio calculates the underlying aspect ratio from any given resolution in the x- and y-direction. The aspect ratio is output without a line break. This enables the direct use in other scripts or programs.</p>

<p align="justify">The calculation is done using the greatest common divisor (GCD) of two integer numbers. If the result does not match the input values, this is due to a suitable aspect ratio. Otherwise, the image is not based on a standard aspect ratio. For example, it has already been edited.</p>

# References

[1].   en.wikipedia.org/wiki/List_of_image_resolutions_used_in_digital_cameras
