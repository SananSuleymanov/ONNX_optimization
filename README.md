# ONNX optimization
This repository contains optimization.ipynb Colab notebook in order to optimize ONNX model by pruning and quantization.

model_1/ folder conttains tf formatted model and as well as .tflite model which is converted from tf model and optimized by default parameters.

pruned_model.onnx is the last model which quantized and then pruned while because of the error related to the converted layer name it was not possible to run inference and check the speed. 

