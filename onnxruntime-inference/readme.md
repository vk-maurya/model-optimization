# BERT Inference Time and Latency Comparison: PyTorch vs. ONNX Runtime

## Overview
This Jupyter Notebook provides a comparative analysis of BERT model inference times and latencies using PyTorch and ONNX Runtime on a GPU. The goal is to evaluate the performance improvements when switching from PyTorch to ONNX Runtime for BERT inference.

## Results Summary

### Inference Time

**PyTorch Inference Time**: 98 seconds (1 minute 38 seconds)

**ONNX Runtime Inference Time**: 68 seconds (1 minute 8 seconds)

**Speed Improvement**: ONNX Runtime is approximately `30.61%` faster than PyTorch.

#### Latency Analysis

**PyTorch Latency**: 19.55 milliseconds

**ONNX Runtime Latency**: 13.09 milliseconds

**Latency Improvement**: ONNX Runtime has an average latency that is approximately `33.06%` lower than PyTorch.