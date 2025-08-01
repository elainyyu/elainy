# Image Classification using Jetson Inference

[https://youtu.be/xMBvlL8zV3M?feature=shared](Video)

This project demonstrates how to classify images using a pre-trained image classification model on NVIDIA Jetson devices with the `jetson-inference` library.

## File

- `main.py` — A Python script that loads an image, classifies it using a specified neural network model, and prints the classification result.

## Requirements

- NVIDIA Jetson device (e.g., Jetson Nano, Xavier, TX2)
- [JetPack SDK](https://developer.nvidia.com/embedded/jetpack) installed with Jetson Inference
- Python 3
- `jetson-inference` and `jetson-utils` Python libraries (pre-installed with JetPack)

## Usage

```bash
python3 main.py <image_filename> --network <model_name>
