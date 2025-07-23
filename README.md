# CSCA-5642 GAN Picture Generation Project

This project implements a CycleGAN to transform photographs into Monet-style paintings for the Kaggle "I'm Something of a Painter Myself" competition. Using TensorFlow, the model trains on unpaired datasets of photos and Monet paintings (256x256 RGB images) to learn bidirectional mappings. 

## Directory Structure
Below is the directory structure of the project:

  ├── data/<br>
  │  ├── monet_jpg.zip<br>
  │  └── sample_photo_jpg.zip<br>
  ├── output/<be
  │  └── images.zip<br>
  └── monet-Style-CycleGAN-Generator.ipynb<br>


## Files
- data/monet_jpg.zip: Input monet painting in jpg format.
- data/sample_photo_jpg.zip: Input photo to be used for painting generation.
- output/images.zip: Zip file containing 7000 images generated
- monet-Style-CycleGAN-Generator.ipynb: The main Jupyter Notebook containing the CycleGAN code. 

## Author
- **Author**: Alexander Meau
- **Email**: alme9155@colorado.edu
