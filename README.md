# Embedding Augmentation and Hybrid Convolutional Transformers for Ship Wake Classification
## By: Siddharth Sandu
This zip file contains three folders for each distribution, which would further include all the Jupyter notebooks corresponding to each model. The folder names are:

●	NF (Noise Free)

●	N (Noisy Images)

●	ND (Denoised Images)

One would need to generate two Numpy arrays corresponding to the processed images and the respective labels called ‘resized_images.npy’ and ‘labels.npy’ respectively. These arrays can be generated through the Data_Preprocess notebook which has also been provided.

Each distribution would contain a separate Jupyter notebook for all the tested models which are:

●	MobileNetV2

●	DenseNet121

●	ResNet50

●	ViT

●	ConvNext

The original dataset can be downloaded from here for reproducing the results: https://data.bris.ac.uk/data/dataset/30kvuvmatwzij2mz1573zqumfx
