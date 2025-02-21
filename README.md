# CART498-Postcards-from-my-jungle
https://lydiagraveline.github.io/CART498-Postcards-from-my-jungle/ 

# Project Overview

This project was an attempt at generating creatures inspired by medieval manuscripts and illuminated books by training a model on a custom dataset.

For the model training, I sourced images from the Medieval Bestiary (https://bestiary.ca/). I created a subset of 1008 images, resizing them to 256x256 pixels and applying transformations such as color jittering and random horizontal flipping to increase diversity and improve the model's learning. The model was trained on this dataset for 70 epochs, with a learning rate of 2e-5.

The quality of the generated images could be significantly improved with further model tuning and adjustments. Increasing the dataset size and training the model for a longer period could help.


