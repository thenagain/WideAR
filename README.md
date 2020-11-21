# WideAR
**WideAR** is the implementation of [Pix2Pix](https://arxiv.org/abs/1611.07004) for increasing FoV of mobile AR experience.

Pix2Pix is one of the greatest **GAN-based neural network** that learns how to convert between two images.

## Pix2Pix_WideAR
**Pix2Pix_WideAR** learns how to fill external side of image.

This is a example output of Pix2Pix_WideAR.
![example_output](/img/example_output.png)

## DatasetMaker_WideAR
**DatasetMaker_WideAR** just makes 3 types of dataset(train/test/val) from a video file.

Because of my purpose, DatasetMaker masks external side of every frame from a video and makes data which fulfill requirements of Pix2Pix input.


## Future Work
- Realtime FoV increasing in AR experience
- Refine dataset for robust generator
