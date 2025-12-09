# Edge_Vision
## Introduction
We are actively conducting research focused on the design and optimization of lightweight AI models capable of running efficiently on edge devices. Our primary goal is to develop high-performance AI solutions for real-time perception in autonomous driving scenarios. Key research activities include leveraging edge devices such as the Jetson AGX Orin to implement and optimize these models. By utilizing state-of-the-art optimization techniques such as Neural Architecture Search (NAS), Pruning, and Quantization, we aim to minimize memory usage and inference time while maintaining stable performance.
Additionally, our research explores hardware acceleration and parallel processing tools to identify and address performance bottlenecks, providing optimal solutions tailored for autonomous driving systems.




# Use in a Local

# YOLO-series
YOLOv5 ~ v11 for Inference at Local & Jetson board

## Installation
<pre> <code> pip install ultralytics </code> </pre>
<pre> <code> pip install -r requirements.txt </code> </pre>


## yolov5 github
https://github.com/ultralytics/yolov5
### Inference using webcam
TBD

## yolov6 github
https://github.com/meituan/YOLOv6
### Inference using webcam
<pre> <code> python3 tools/infer.py --weights yolov6n.pt --source 0 --webcam --yaml data/coco.yaml --view-im </code> </pre>

## yolov7 github
https://github.com/WongKinYiu/yolov7
### Inference using webcam
<pre> <code> python3 detect.py --weights yolov7.pt --conf 0.25 --source 0 --view-img --view-im </code> </pre>

## yolov8 github
https://github.com/autogyro/yolo-V8
https://docs.ultralytics.com/ko/models/yolov8/
### Inference using webcam
<pre> <code> python3 infer.py --weights yolov8n.pt --conf 0.25 --source 0 --view-img --view-im </code> </pre>

## yolov9 github
https://github.com/WongKinYiu/yolov9
### Inference using webcam
<pre> <code> python3 detect.py --weights yolov9t.pt --conf 0.25 --source 0 --view-img </code> </pre>

## yolov10 github
https://github.com/THU-MIG/yolov10
### Inference using webcam
<pre> <code> python3 app.py --weights yolov10n.pt --conf 0.25 --source 0 --view-img </code> </pre>
and also connect to the link below
<pre> <code> http://127.0.0.1:7860 </code> </pre>

## yolov11 github
https://github.com/THU-MIG/yolov10

### Inference using webcam
<pre> <code> python3 infer.py --weights yolov11n.pt --conf 0.25 --source 0 --view-img </code> </pre>

# Use in a AGX Orin
TBD

# Use in a Orin Nano
TBD


## Contact
Vehicle Intelligence Perception LAB at Gachon University <https://sites.google.com/view/vip-lab>

 - Jhonghyun An, Professor of the Gachon Univ / jhonghyun@gachon.ac.kr
 - Nahyeong Kim, Master's Student of the Gachon Univ / skgud99@gachon.ac.kr
 - Seong Kyu Choi, Master's Student of the Gachon Univ / seongkyu950324@gachon.ac.kr
 - Young Jae Cheong, Master's Student of the Gachon Univ / bluebull777@gachon.ac.kr
 - Yejun Lee, Master's Student of the Gachon Univ / dldpwns001@gachon.ac.kr
 - Sungju An, Master's Student of the Gachon Univ / samsj1209@gachon.ac.kr
 - Siwoo Kim, Master's Student of the Gachon Univ / ksw5830@gachon.ac.kr



-------------
