# VizStudio_ACES_config
Custom ACES config file for the Visualization Studio.
Created by Mike Schmitt, March 2022

This is a modified ACES config combining elements from the
Substance Painter OCIO_v1 config and some of the newer naming conventions from RedShift ocio_v2 config
modified for the Visualization Studio

We changed some of the color space names to simplify:

linear = linear-Rec.709-sRGB (v2) = Utility - Linear - sRGB (v1)

sRGB = sRGB (v2) = Utility - sRGB - Texture (v1)


We renamed this View, since it's much much easier to say and type.  
It is our default View and Output Transform for sRGB images.

ACESvid = Invert ACES SDR 1.0 video (v2) = Output - sRGB (v1)


A "Dome-look" LUT has also been added to simulate the low contrast of the Morrison Planetarium dome on our sRGB computer monitors.
