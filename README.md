# Pixacular
 
Heya Reading this I hope you are fine and I'm glad you are here, let me tell you , you are AWESOME. 
At first i would like to tell you why i named it "PIXACULAR", so pixacular is inspired with the idea of how exactly this thing works + what was my reaction on watching "How this thing worked."
 
So the idea is COLORIZING the old or black and white PICS by using Artificial Intelligence Modules ain't it SPECTACULAR.

(o: Apologies for being on height of logiclessness LOL :o )


# INTRODUCTION

This work is originally inspired from the research work of Richard Zhang, Phillip Isola, and Alexei A. Efros from University of California, Berkeley.
The original work was called Colorful Image Colorization and reference to their original paper can be found in the PDF attached at the modules of repository.


# ABOUT THE PROJECT
 
This Project is based upon the fact of Colorizing the old / Black and white pictures automatically by effective utilization of Convolutional Neural Network.

The project uses the CIELAB color space, CIE L*a*b* (CIELAB) is a color space specified by the International Commission on Illumination (French Commission internationale de l'éclairage, hence its CIE initialism). It describes all the colors visible to the human eye and was created to serve as a device-independent model to be used as a reference.

The three coordinates of CIELAB represent the lightness of the color (L* = 0 yields black and L* = 100 indicates diffuse white; specular white may be higher), its position between red/magenta and green (a*, negative values indicate green while positive values indicate magenta) and its position between yellow and blue (b*, negative values indicate blue and positive values indicate yellow). The asterisk (*) after L, a and b are pronounced star and are part of the full name, since they represent L*, a* and b*, to distinguish them from Hunter's L, a, and b, described below.

Since the L*a*b* model is a three-dimensional model, it can be represented properly only in a three-dimensional space.Two-dimensional depictions include chromaticity diagrams: sections of the color solid with a fixed lightness. It is crucial to realize that the visual representations of the full gamut of colors in this model are never accurate; they are there just to help in understanding the concept.

Because the red-green and yellow-blue opponent channels are computed as differences of lightness transformations of (putative) cone responses, CIELAB is a chromatic value color space.

Unlike the RGB and CMYK color models, Lab color is designed to approximate human vision. It aspires to perceptual uniformity, and its L component closely matches human perception of lightness.

This Project Uses Deep learning models, trained over a 1.3 million coloured images which during training were decomposed using LAB model and used as an input feature "L" and classification labels ("a" and "b").

Now having trained models available publically any black and white image can be colorized using them by applying a simple Feed Forward Convolutional Neural Network.

The input it takes from the Image is the "L" component that is the light which when passed from Neural Net decomposes into "A" and "B" which again added with "L" produces an Image colored Artificially.

Isn't it spectacular ,how the machine understands the composition of colors and contrast to produce its own sense of colorizing the uncoloured pics.

