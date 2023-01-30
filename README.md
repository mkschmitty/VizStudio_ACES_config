# VizStudio_ACES_config
Custom ACES config file for the Visualization Studio.
Created by Mike Schmitt, March 2022

This is a modified ACES config combining elements from the
Substance Painter OCIO_v1 config and some of the newer naming conventions from RedShift ocio_v2 config
modified for the Visualization Studio

We modified the ACES naming convention slightly to simplify.  Also, to keep some of the color spaces backwards compatible with older nuke scripts, namely:

*linear* = "Utility - Linear - sRGB" (v1) or "linear-Rec.709-sRGB" (v2)

*sRGB* = "Utility or  sRGB - Texture" (v1) or "sRGB" (v2)

*ACESvid* = "ACES SDR 1.0 video" (v2) or "Output - sRGB" (v1)
-- this is used only as a View Transform and Output Color Transform.  We shortened the name since "ACES SDR 1.0 video" is a mouthful

*Dome-look* = A custom View LUT to simulate the Morrison Planetarium dome color response on an sRGB monitor.  
