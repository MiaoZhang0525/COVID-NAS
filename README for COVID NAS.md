# COVID-CT


**We try to apply neural architecture search methods for COVID-CT-Dataset. We have considered 3 situations. The fist situation is that we directly search on COVID dataset. The second situation is that we train the supernet with CIFAR10, while evaluating architecture on COVID dataset after transfer learning during the architecture search. The third situation is that we train the supernet with ImageNet, while evaluating architecture on COVID dataset after transfer learning during the architecture search. We implementate our framework on DARTS and GDAS for the three situation.**

 

### First situation

The code could be found in `./\DenseNet169/DARTS_train_search_on_COVID.ipynb`, and `./\DenseNet169/GDAS_train_search_on_COVID.ipynb`.


### Second situation

The code could be found in `./\DenseNet169/DARTS_train_search_on_CIFAR_for_COVID.ipynb`, and `./\DenseNet169/GDAS_train_search_on_CIFAR_for_COVID.ipynb`.


### Third situation

The code could be found in `./DenseNet169/DARTS_train_search_on_ImageNet_for_COVID.ipynb`, and `./DenseNet169/GDAS_train_search_on_ImageNet_for_COVID.ipynb`.

### Direct transfer from trained models

The code of direct transfer the best-found models trained on CIFAR and Imagenet could be found in `./DenseNet169/CIFAR_model_transfer_to_COVID.ipynb`, and `./DenseNet169/ImageNet_model_transfer_to_COVID.ipynb`.


### Baseline Performance
The details are in README for `DenseNet_predict.md`

