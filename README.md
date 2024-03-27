# Mask R-CNN for Object Detection and Segmentation

This repository implements Mask R-CNN using Python 3, Keras, and TensorFlow. The model provides bounding boxes and segmentation masks for each instance of an object in an image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

## Features

- Object detection and instance segmentation.
- Source code for Mask R-CNN built on FPN and ResNet101.
- Training code for MS COCO dataset.
- Pre-trained weights for MS COCO.
- Jupyter notebooks for visualizing the detection pipeline.
- Evaluation on MS COCO metrics (AP).
- Example of training on your own dataset.

## Getting Started

- `demo.ipynb`: Example usage with pre-trained model on MS COCO.
- `train_shapes.ipynb`: Demonstrates training Mask R-CNN on a toy dataset (Shapes).

## Step-by-Step Detection

For debugging and understanding the model, there are several notebooks available:

- `inspect_data.ipynb`: Visualizes pre-processing steps for training data.
- `inspect_model.ipynb`: Provides visualizations of each step in the detection pipeline.
- `inspect_weights.ipynb`: Inspects weights of a trained model.

## Training on MS COCO

Pre-trained weights for MS COCO are provided. Training and evaluation code can be found in `samples/coco/coco.py`.

## Training on Your Own Dataset

Extend two classes: `Config` and `Dataset`. See examples in provided notebooks and samples.

## Requirements

- Python 3.4, TensorFlow 1.3, Keras 2.0.8.
- Additional requirements listed in `requirements.txt`.

## Citation

Use the provided BibTeX citation to reference this repository.

## Contributing

Contributions are welcome, including speed improvements, training on other datasets, accuracy improvements, visualizations, and examples.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Special thanks to the contributors and projects using this model.
