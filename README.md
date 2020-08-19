# Hypespectral Data Visualization and Classification
## The repository contains the implementation of PCA + SVM and PCA + Hybrid(2D+3D) CNN implemenatation techniques on Hyperspectral Images(Indian Pines Dataset):

### Hyperspectral_Analysis(Visualization)_+_SVM.ipynb
Data Analysis - Data anlysis of the indian pines hyperspectral image:

* Visualizing pixels of the hyperspectral image.
* Bar plot w.r.t class labels of the hyperspectral image.
* Box Plot w.r.t the class labels and bands of hyperspecral image.
* Distribution Plot w.r.t the bands of hyperspecral image

PCA : Dimensionality Reduction using PCA.

Classifier: The support vector machine(SVM) classifier is used to classsify the pixels of the HSI with classification report and the confusion matrix, classification map of the classifier is visualized.

For above implementation please refer: https://github.com/aditis1204/Hypespectral_Visualization_Classification/blob/master/Hyperspectral_Analysis(Visualization)_%2B_SVM.ipynb 

### Hypespectral_CNN(2d_+3d).ipynb

PCA : Dimensionality Reduction using PCA.

Classifier:
The Hyperspectral_CNN(2d+3d) is spectral-spatial 3D-CNN followed by spatial 2D-CNN. The 3D-CNN facilitates the joint spatial-spectral feature representation from a stack of spectral bands. The 2D-CNN on top of the 3D-CNN further learns more abstract level spatial representation.


For above implementation please refer:
https://github.com/aditis1204/Hypespectral_Visualization_Classification/blob/master/Hypespectral_CNN(2d_%2B3d).ipynb
