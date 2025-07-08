# SSD-Scratch
The SSD-Scratch dataset contains three sub-datasets: neu, neu_A, and neu_mix.

**neu** ：Refers to the 464 remaining unlabeled images that were assigned pseudo-labels through the MOSD-UNet model.

**neu_A**：The model first undergoes supervised training using 464 annotated images from the training set along with their corresponding true labels, and then its performance is verified on the test set.

**neu_mix**： Using all 928 training images and their mixed labels (including 464 real labels and the high-confidence pseudo labels selected from the remaining 464 images), the model was re-trained, and its performance was evaluated on the same test set.

Among them, neu_A and neu_mix include the training set "train" and the validation set "val", and "train" and "val" each contain images and masks. The specific structure of the dataset branches can be referred to in the README of the MOSD-UNet model.

**SSD-Scratch**：The scratch dataset selected from the NEU-seg dataset includes all the scratch images and their labels.


**When using this dataset, please pay attention to the following points:
  
  1.Please ensure that relevant laws, regulations and ethical guidelines are observed when using data sets for research and development.
  
  2.The use of data sets is limited to academic research or non-commercial purposes.
  
  3.Please respect the copyright of the dataset and do not use the dataset for commercial purposes without permission.**
