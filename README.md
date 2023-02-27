# ONNX optimization
This repository contains optimization.ipynb Colab notebook in order to optimize ONNX model by pruning and quantization.
The inference speed before quantization and pruning is 1.67s.

model_1/ folder conttains tf formatted model and as well as .tflite model which is converted from tf model and optimized by default parameters. The inference runned on the tflite model is 1.65s.

pruned_model.onnx is the last model which is dynamically quantized and then pruned using onnxoptimizer library. The inference speed after quantization and pruning is 0.08s.
