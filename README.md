# WideAR
**WideAR** is the implementation of [Pix2Pix](https://arxiv.org/abs/1611.07004) for increasing FoV of mobile AR experience.
Pix2Pix is one of the greatest GAN-based neural network that learns how to convert between two images.

## Mobile AR Experience Problem
Recently, FoV of smartphone camera is increasing.
But mobile AR tracking system relies on differences of multiple cameras' feeds, and therefore mobile AR experience can only use the narrowest camera's feed which offers relatively accurate tracking.
I thought this is why we feel some barriers between AR experience and real. So I attempted to increase FoV of AR experience using Pix2Pix.

## DatasetMaker_WideAR
**DatasetMaker_WideAR** just makes 3 types of dataset(train/test/val) from a video file.
For my purpose, DatasetMaker masks external side of video frame and makes data which fulfill requirements of Pix2Pix input.

## Pix2Pix_WideAR
**Pix2Pix_WideAR** learns how to fill external side of image.
This is a example output of Pix2Pix_WideAR.
![example_output](/img/example_output.jpg)

## Future Work
- Realtime FoV Increasing in AR experience
- Robust
