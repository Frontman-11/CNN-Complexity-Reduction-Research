# CNN-Complexity-Reduction-Research
A research aimed at building efficient lightweight CNN model for computer vision while maintaining the state of the art accuracy.

The notebook provided in this project serves as a pipline for training this model across the dataset. to train with any dataset, you just need to download the neded dataset from the second cell. Note that if the dataset is not gray scaled images then the dimention expansion lines of code should be commented. Note also that for none gray scaled images the dataset may not be visualised as the code works only for the gray scaled images. hence to visualise the original and the augmented version of datasets like cifar10 you would need to modify the code if you find it necessay, otherwise comment the code cells to avoid errors.
Finally, the last change lies at the input shape which must be manually, otherwise you make it read the input shape dynamically. I left it to be changed manually so as to give a sense and a constant reminder of what we are dealing with.

Besides this, no other changes are required in this notebook. hence the pipeline can easily be trained for the handwritten digit MNIST, the fashion MNIST and the cifar10 dataset without many changes (in fact the two MNIST datasets need no modification in the code).
