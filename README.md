# Neural Style Transfer

This repository contains the implementation of the original Neural Style Transfer (NST) algorithm as described in the paper by Gatys et al. It also includes additional scripts for reconstructing only the content or the style of the image, providing a deeper understanding of how NST works.

## Repository Structure

## Requirements

To set up the environment, you need to have Conda installed. Run the following command to create the necessary environment:

```sh
conda env create -f environment.yml
conda activate nst
```

## Usage

### Performing Neural Style Transfer

To perform neural style transfer, you can use the `neural_style_transfer.py` script. You need to specify the paths to the content and style images along with the output path. Here's an example of how to run the script:

```sh
python neural_style_transfer.py --content data/content-images/your-content-image.jpg --style data/style-images/your-style-image.jpg --output data/output-images/your-output-image.jpg
```

### Reconstructing Content or Style

To reconstruct only the content or the style of an image, you can modify the script parameters as needed. Detailed instructions for these scripts will be provided in the respective script files or via command-line help options.

## Directory Descriptions

- **data/content-images/**: This directory should contain the images you want to use as content images.
- **data/examples/**: This directory contains example results of neural style transfer.
- **data/output-images/**: This directory is where output images will be saved after processing.
- **data/style-images/**: This directory should contain the images you want to use as style images.
- **models/definitions/**: This directory includes the definitions of the models used for neural style transfer.
- **utils/**: This directory contains utility scripts and helper functions.
- **environment.yml**: This file contains the conda environment configuration needed to run the project.
- **neural_style_transfer.py**: This is the main script to run the neural style transfer algorithm.

## References

This code is based on the paper:
- Gatys, L. A., Ecker, A. S., & Bethge, M. (2016). *Image Style Transfer Using Convolutional Neural Networks*. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR).

## Credits and Inspiration 
[gordicaleksa/pytorch-neural-style-transfer ](https://github.com/gordicaleksa/pytorch-neural-style-transfer.git)
