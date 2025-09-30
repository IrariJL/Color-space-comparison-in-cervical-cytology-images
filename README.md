# Color-space-comparison-in-cervical-cytology-images
A CNN implementation to classify cervical cytology samples in five and two classes using SIPAKMED dataset. Six color space transformations were compared, the individual RGB channels, and combinations of these channels. This work compred the results through VGG-16 model. The results obtained is presented in the article: **Over Color Spaces Comparison of Isolated Cervix Cells for Morphology Classification**

If you are going to use this repository, please cite our work:
*Jiménez-López I., Valdez-Rodríguez J.E. and Moreno-Armendáriz M. A. (2025). Over Color Spaces Comparison of Cytology Samples Classification. (Publish pending).*

****************************************************************************
In this repository, you can find the code for both binary and multiclass classification tasks, as well as for preprocessing the Sipakmed database to resize the images and apply zero-padding, obtaining images of size 256×256.
  - k_fold_color_space_binary.ipynb
  - k_fold_color_spaces_5class.ipynb
  - 
