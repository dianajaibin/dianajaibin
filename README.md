# Microarray Work
## [[Paper]](https://dergipark.org.tr/sdufenbed/issue/39838/453462)[[Datasets]](https://github.com/kivancguckiran/microarray-data)

DNA Microarray Gene Expression Data Classification Using SVM and MLP with Feature Selection Methods Relief and LASSO.

If you are planning to use this code in your research, please cite this [paper](https://dergipark.org.tr/sdufenbed/issue/39838/453462).

## Dataset
Datasets are DNA microarray gene expression data. [Dataset Link](https://github.com/kivancguckiran/microarray-data).

## Methods
We are using LASSO and Relief for Feature Selection and SVM and MLP for classification.

## Download

```
git clone https://github.com/kivancguckiran/microarray-classification
```

## Usage
*data* folder should be filled with the dataset you want to classify.

### Examples
Select features using Relief from *alon* dataset.
```
python relieff.py alon
```
Select features using LASSO from *borovecki* dataset.
```
python lasso.py borovecki
```
Classify using MLP with Relief features with *subramanian* dataset.
```
python classify_with_mlp.py subramanian relief
```
Classify using SVM with LASSO features with *sun* dataset.
```
python classify_with_svm.py sun lasso
```
