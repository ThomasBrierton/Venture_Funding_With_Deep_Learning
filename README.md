# Venture_Funding_With_Deep_Learning

This Deep Learning project utilizes a neural network to predict the liklihood of success amongst startups applying for venture funding. The data, imported from the CSV file, contains 34,000 applicants who have received funding in the past. The venture capitol firm, Alphabet Soup, can use this data and neural network to aid their investment decisions for future applicants. 

---

## Technologies

This project uses [Google Colab](https://colab.research.google.com/?utm_source=scs-index) and the standard Python 3.8 libraries. This project requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation.
- [Path](https://pypi.org/project/path/) - implements path objects as first-class entities, allowing common operations on files to be invoked on those path objects directly.
- [sklearn](https://scikit-learn.org/stable/) - HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple.
- [Tensorflow](https://www.tensorflow.org/) - TensorFlow is an end-to-end open source platform for machine learning.

---

## Installation

The following dependencies must be installed before running the application (excluding Apple computers with M1 chip):
```
pip install -U scikit-learn
pip install --upgrade tensorflow
```
Verify the installation:
```
conda list scikit-learn
python -c "import tensorflow as tf;print(tf.__version__)"
python -c "import tensorflow as tf;print(tf.keras.__version__)"
```
For computers operating on Apple's M1 chip, [Google Colab](https://colab.research.google.com/?utm_source=scs-inde) should be used with the following imports:
```
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
from pathlib import Path
```
---

## Methods

To complete this deep nerual network, the following steps were performed:

1. Prepare the Data for Use on a Neural Network Model.
2. Compile and Evaluate a Binary Classification Model Using a Neural Network.
3. Optimize the Neural Network Model.
4. After finishing the models, display the accuracy scores achieved by each model, and compare the results.
5. Save each of your alternative models as an HDF5 file.

---

## Usage

To use the deep neural network model, clone the repository and open the .ipynb file with [Google Colab](https://colab.research.google.com/?utm_source=scs-inde). Import the CSV file and run the mnodel. 

---

## Conclusions

Three alternative models were created to test different methods for improving accuracy and reducing loss. Each model varied slightly in composition, but the results were similar with a loss of 0.6 and an accuracy of 73%. To improve these results, tweaking the models hidden layers, node composition, and activation functions might be helpful. 

## Contributors 

Thomas Brierton and UCB

---

## License

MIT