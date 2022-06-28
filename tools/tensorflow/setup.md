1. create environemnt
```
conda create -n ml python=3.9
conda activate ml
```
2. download tensorflow
```
pip install tensorflow
```
3. test if tensorflow if donwloaded
```
python
import tensorflow as tf
tf.__version__
physical_devices = tf.config.list_physical_devices("GPU")
```
