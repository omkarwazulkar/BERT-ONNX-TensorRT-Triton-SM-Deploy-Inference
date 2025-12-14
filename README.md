# 🚀 End-to-End Model + ONNX + TensorRT + Triton + SageMaker Multi-Model Endpoint (MME)

This repository demonstrates a complete, production-grade workflow for:

- Using deep learning models (**BERT** and **ResNet-50**)
- Converting models from native frameworks to **ONNX**
- Optimizing ONNX models into **TensorRT engines**
- Packaging models for **NVIDIA Triton Inference Server**
- Deploying models on **Amazon SageMaker Multi-Model Endpoints (MME)**
- Running **GPU-accelerated inference** with dynamic model loading and unloading

The workflow is **framework-agnostic** and applies consistently to both  
**NLP (BERT)** and **Computer Vision (ResNet-50)** use cases.

## Prerequisites

This tutorial uses an **Amazon SageMaker Notebook Instance** with the following configuration:

- **Instance type:** `g5.2xlarge`
- **Storage:** 20 GB
