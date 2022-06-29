1. create environemnt
```
conda create -n ml python=3.9
conda activate ml
```
2. download tensorflow
tensorflow setup for apple M1 (June 2022)
* https://developer.apple.com/metal/tensorflow-plugin/
* https://www.youtube.com/watch?v=_1CaUOHhI6U&t=427s

3. test if tensorflow if donwloaded
```
python
import tensorflow as tf
tf.__version__:q
physical_devices = tf.config.list_physical_devices("GPU")
```
4. (optional) install TensorFlow Datasets
```
python -m pip install tensorflow-datasets
```
5. inital common data science packages
```
conda install jupyter pandas numpy matplotlib scikit-learn
```
6. start Jupyter Notebook
```
jupyter notebook
```
