# Latent space representation learning by using UMAP-
The aim of this project is to provide visualizations of the 8-dimensional latent space projected into a 2-dimensional space using paired linked variational autoencoders. The dataset contains 21 different classes of shapes, each with a corresponding spectrum response. 

**Requirements**
  - Python = 3.7.16
  - Tensorflow-gpu == 2.4.0
    - Cuda = 11.0
    - Cudnn = 8.0

# Results 
This figure shows the visualizations of 8 dimensional latent space for shape and spectrum projected into 2 dimensional latent space. 
![UMAP Results Plot](https://raw.githubusercontent.com/22510064/UMAP-Representation-/main/UMAP_results_plot.png)


Basically, we have 21 classes of shapes included in the dataset. We can toggle the visibility of each class to view them individually.
This figure shows the shape and spectrum for class label 4.

![UMAP Shape](https://github.com/22510064/UMAP-Representation-/blob/main/UMAP_shape.png)


![UMAP Spectrum](https://github.com/22510064/UMAP-Representation-/blob/main/UMAP_spectrum.png)



# Installation
```bash
$ git clone https://github.com/22510064/UMAP-Representation-
$ pip install -r requirements.txt
