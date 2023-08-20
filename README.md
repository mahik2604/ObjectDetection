# Object Detection with SSD MobileNet v3

This repository contains code for performing object detection using the SSD MobileNet v3 model pretrained on the COCO dataset. The code uses the OpenCV library to load the model and perform object detection on input images.

## Description

This Jupyter Notebook demonstrates how to perform object detection using the SSD MobileNet v3 model. The notebook loads the pre-trained model, reads an input image, detects objects in the image, and overlays bounding boxes and class labels on the image to highlight detected objects.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`) library
- Matplotlib library (`matplotlib`)

## Setup

1. Install the required Python packages using pip:

   ```bash
   pip install opencv-python matplotlib
   ```

2. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/mahik2604/ObjectDetection.git
   ```

## Usage

1. Make sure you have the required configuration and label files in the appropriate paths.

2. Open the `Object_Detection.ipynb` Jupyter Notebook using Jupyter or JupyterLab.

3. Run the notebook cell by cell to execute the code.

4. The notebook will display the input image with bounding boxes and class labels overlayed on the detected objects.

## Configuration Files

- `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`: This configuration file defines the architecture of the SSD MobileNet v3 model. You can download it from [this GitHub Gist](https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7).

## Labels

- `Labels.txt`: This file contains the class labels used by the COCO dataset. You can find the file [here](https://github.com/pjreddie/darknet/blob/master/data/coco.names).

Please download and place these files in the appropriate paths before running the notebook.

## Contributing

Contributions to this repository are welcome. If you find any issues or want to enhance the code, feel free to open a pull request.

## License

This project is licensed under the [MIT License](https://github.com/mahik2604/ObjectDetection/blob/main/LICENSE).
