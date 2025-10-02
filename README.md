# Overview of computer vision techniques/models
A repository of scripts implementing computer vision techniques and machine learning models in the field of image processing. Functions implemented in this repository utilizes open-source libraries and publically-available datasets to showcase the use-case and limitations of each tool.

## Image processing techniques
- Vignetting: Techniques for creating darker edges in images, also known as vignetting.
- Flat-field correction: Techniques for correcting darker edges (or vignette effects) in images to smooth out image intensities.
- Morphological operations: Binary mask processing operations to improve the quality of generated masks for object detection in images.
- Low-pass filters: Filters that remove high-frequency noises while allowing low-frequency signals to pass through, useful for providing smoothing and blurring effects in images.
- High-pass filters: Filters that remove low-frequency noises while allowing high-frequency signals to pass through, useful for sharpening effects and detecting sharp edges in images.
- Otsu Thresholding: A simple method for generating a binary mask of objects in images, useful for object detections.
- Watershed: An opencv algorithm that involves creating basins and expanding them to segment objects in images.
- Image denoising: Technique to reduce graininess and decolorization in images to improve image quality.

## Open-source libraries with image analyses tools
- [Deepspot](https://github.com/cbib/DeepSpot): Deep-learning method for enhancement of fluorescent spots in microscopy images.
- [Cellpose](https://github.com/MouseLand/cellpose): A neural network based method trained specifically for cell segmentation in images.
- [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything): An AI model from MetaAI that takes in user-specified prompts to segment objects in images.
- [BigFISH](https://github.com/fish-quant/big-fish) spot detection in microscopy images: Detects fluorescent spots in microscopy images.
- [trackpy](https://github.com/soft-matter/trackpy) spot detection in microscopy images: Detects fluorescent spots in microscopy images.

## Machine Learning Model add-ons
- Convolutional Block Attention Module (CBAM): Lightweight attention module easily integrateble to different types of model architecture to improve performance.
