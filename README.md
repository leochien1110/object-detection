# object-detection
## Introduction
This dnn object detection project is for my personal practice and test. 

# Files
- `bbox_stream.py`: use yolov4 model to recognize objects and draw bounding boxes. It can read from a webcam or a video file.
- `object_detect_stream.py`: use google net to recognize the object in images.

## Usage
1. Download model files (.names, .weights, .cfg) from the [darknet](https://github.com/AlexeyAB/darknet/releases/tag/yolov4) or other resrouces to the `/model` folder.
1. Change the model pathes in the python script.
    - `"model/coco.names"`
    - `yolo_config_path = "model/yolov4-tiny.cfg"`
    - `yolo_weights_path = "model/yolov4-tiny.weights"`
1. Specify image/video frame width: `frame_width = 1280`.
1. Specify using CUDA or not. Change it to `True` if **NVIDIA** GPU is available. 

## Train Customized Model
TBC

### Labeling
TBC

## Reference
 - AlexeyAB/darknet: https://github.com/AlexeyAB/darknet/releases/tag/yolov4
 - 李謦伊's Medium: https://medium.com/ching-i/yolo-c49f70241aa7
- dschwalm/deeplearning: https://github.com/dschwalm/deeplearning
