# GEARS-Quantization


The goal is to optimize the MASK-RCNN-FPN model, which is trained on Facebook’s detectron2 framework, to reduce its prediction time due to its heavy size and slow processing speed.

In this study, a solution is proposed to address the absence of quantization capabilities in Detectron2. By converting the PyTorch object detection model into a TorchScript representation and applying dynamic quantization techniques, the model’s parameters and activations are compressed into 8-bit integer formats. This optimization approach reduces memory usage and computational complexity, paving the way for enhanced execution efficiency.
