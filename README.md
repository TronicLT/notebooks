# Notebooks
General Jupyter notebooks

## List of notebooks
  1. [UCF 101 - Action Bank](./ucf101_actionbank.ipynb): The notebook quantifies Action Bank features for action recognition using the UCF101 dataset.
  2. [Supervised dimensionality reduction](./supervised_dimentionality_reduction.ipynb): Notebook explains and implements [MDA/LDA](https://en.wikipedia.org/wiki/Linear_discriminant_analysis) for supervised dimensionality reduction.
  3. [AlexNet conversion](./alexnet_conversion.ipynb): This notebook example demonstrates how to convert a network from [Caffe's Model Zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo) for use with `uml` deep learning library (developed during master's work). [AlexNet model](http://dl.caffe.berkeleyvision.org/bvlc_alexnet.caffemodel) trained for
[LSVRC2012](http://image-net.org/challenges/LSVRC/2012/index). The notebook create a set of `uml` layers corresponding to the Caffe model specification (prototxt), then copy the parameters from the caffemodel file into our model. The conversion is verified using [activation maximization](http://yosinski.com/media/papers/Yosinski__2015__ICML_DL__Understanding_Neural_Networks_Through_Deep_Visualization__.pdf).
  4. [Fraud Detection](./fraud_detection.ipynb): Uses [XGBoost trees](http://xgboost.readthedocs.io/en/latest/model.html), [Random forest](https://en.wikipedia.org/wiki/Random_forest) and [Neural networks](http://neuralnetworksanddeeplearning.com/) to classify between fraudulent and normal transactions that occured in two days. The dataset is highly unbalanced.
