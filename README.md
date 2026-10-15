# OnionCheck — ML Models

This repository contains the trained machine learning models developed for OnionCheck, an image-based onion classification project.

## Model Information

- **Architecture:** MobileNetV2
- **Task:** Image classification
- **Classes:** Healthy, Unhealthy
- **Format:** ONNX
- **Inference:** ONNX Runtime

## Usage

The models can be integrated into applications using ONNX Runtime. Input images must be preprocessed according to the model's requirements.

## Limitations

Predictions may be affected by lighting, image quality, backgrounds, and images outside the training distribution. The model's predictions should not be treated as a definitive assessment of onion quality.

## License

