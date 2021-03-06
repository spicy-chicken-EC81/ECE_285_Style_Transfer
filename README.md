# ECE_285_Style_Transfer
This is a project of Style Transfer with Neural Style Transfer and Cycle-GAN developed by Pengkun Li, Jun Hu, Ming Lei and Meng Zhang.

## Requirements:
Install package 'easydict' as follow:    $ pip install --user easydict

## Code organization:
Demo.ipynb                               -- Run a demo which import the trained model from the checkpoint and then apply it on the test set and plot the first 3 images.

NeuralTransfer.ipynb                     -- Use Neural Style Transfer model to achieve Style Transfer between two images.

OurCycleGan_Small_Datasets_Train.ipynb   -- Run the training and validation of our Cycle-GANs model with small datasets.

OurCycleGan_Large_Datasets_Train.ipynb   -- Run the training and validation of our Cycle-GANs model with large datasets.

NeuralStyleTransfer.py                   -- Provide everything for implemention of Neural Style Transfer model in DEMO.ipynb.

OurCycleGan_Small_Datasets.py            -- Provide everything for implemention of Cycle-GANs model with small datasets in DEMO.ipynb.

OurCycleGan_Large_Datasets.py            -- Provide everything for implemention of Cycle-GANs model with large datasets in DEMO.ipynb.

models.py                                -- Basic architectures of Cycle-GANs (Generators and Discriminators).

utils.py                                 -- Include auxiliary functions which are needed during the training process of Cycle-GAN.

check_Ukiyo_e_city                       -- Include trained Cycle-GANs model of Ukiyo_e and city with small datasets.

check_Romanticism_forest                 -- Include trained Cycle-GANs model of Romanticism and forest with small datasets.

check_Rococo_field                       -- Include trained Cycle-GANs model of Rococo and field with small datasets.

check_Ukiyo_e_city_max                   -- Include trained Cycle-GANs model of Ukiyo_e and city with large datasets.

check_Romanticism_forest_max             -- Include trained Cycle-GANs model of Romanticism and forest with large datasets.

check_Rococo_field_max                   -- Include trained Cycle-GANs model of Rococo and field with large datasets.

All sixs folders are needed to implement the demo. Please create them  in the same folder that contains DEMO.ipynb and upload their corresponding files. Those files can be downlaod through this dir: <br>
https://drive.google.com/drive/folders/1oIX-J0RH8npcyDHh8MjWIyjfmTeHjton?usp=sharing

## code reference:
NeuralTransfer.ipynb is constructed based on this website: <br>
https://pytorch.org/tutorials/advanced/neural_style_tutorial.html

model.py, utils.py, OurCycleGan_Small_Datasets_Train.ipynb, OurCycleGan_Large_Datasets_Train.ipynb, OurCycleGan_Small_Datasets.py and OurCycleGan_Large_Datasets.py are constructed based on the code in this github respository: <br>
https://github.com/aitorzip/PyTorch-CycleGAN.git

OurCycleGan_Small_Datasets_Train.ipynb, OurCycleGan_Large_Datasets_Train.ipynb, OurCycleGan_Small_Datasets.py and OurCycleGan_Large_Datasets.py use the checkpoint method mentioned in the nntools.py
