# Computer Vision Assignment: YOLOv5 with CBAM

## Project Description
This project is an improvement based on [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5). 
We integrated the **CBAM (Convolutional Block Attention Module)** into the backbone network to enhance feature extraction capabilities.

## Innovation
- **Method:** Added CBAM attention mechanism to the Backbone layer.
- **File Modified:** - `models/common.py`: Added CBAM class definition.
  - `models/yolov5.py`: Registered CBAM module.
  - `models/yolov5s_cbam.yaml`: Custom network configuration.

## Performance
Compared to the baseline, the improved model shows better convergence and precision on the test dataset.
![Training Results](results.png)  <-- 如果你上传了results.png，这里会自动显示
