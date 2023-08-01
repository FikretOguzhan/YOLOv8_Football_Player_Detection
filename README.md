# YOLOv8_Football_Player_Detection

![yolov8](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/7d96aad1-d027-4d81-8ecd-9f6bd0db3c50)

### What is YOLO?
YOLO (You Only Look Once) is a popular deep learning algorithm in the field of object detection. YOLO stands out among object detection models for its fast and real-time performance.

YOLO is used to detect and classify objects in an image or video stream. Instead of dividing the input image into small parts, the algorithm examines the entire image in a single pass to predict the locations and classes of objects. This makes YOLO faster than other traditional object detection methods.

YOLO consists of two main components:

1- Object Detection: It identifies objects in the input image and predicts a class label and bounding box for each object. This allows it to detect regions in an image where multiple objects are present.

2- Object Classification: It recognizes the detected objects and classifies them accurately based on class labels.

The fast and real-time capabilities of YOLO enable its usage in various applications such as autonomous driving, video surveillance, object tracking, object counting, security systems, games, and many other fields.

### YOLOv8
##### What's new in YOLOv8?
It is built as a unified framework for training Object Detection, Instance Segmentation, and Image Classification models.
Here are some key features about the new release:

-User-friendly API (Command Line + Python).
-Faster and More Accurate.
-Supports
  -Object Detection,
  -Instance Segmentation,
  -Image Classification.
-Extensible to all previous versions.
-New Backbone network.
-New Anchor-Free head.
-New Loss Function.
YOLOv8 is also highly efficient and flexible supporting numerous export formats and the model can run on CPUs & GPUs. There are five models in each category of YOLOv8 models for detection, segmentation, and classification. These are YOLOv8n, YOLOv8s, YOLOv8m, YOLOv8I, YOLOv8x. YOLOv8 Nano is the fastest and smallest, while YOLOv8 Extra Large (YOLOv8x) is the most accurate yet the slowest among them. In this project, we use YOLOv8s.
### Steps
#### Step 1: Dataset
In this project, raw data was first obtained from kaggle. The data received from Kaggle consisted of 511 unannotated images. One of the most logical and useful ways to annotate these images is to use Roboflow. You can access Roboflow and kaggle dataset from the links below.

Kaggle Dataset: https://www.kaggle.com/datasets/ihelon/football-player-segmentation
Roboflow: https://universe.roboflow.com/

#### Step 2: Annotating
As I mentioned before, I used roboflow at this stage and you can see images of this stage below.

![roboflow1](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/45b62fca-488c-4c24-ad70-5a525b3275d5)

![roboflow2](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/31876f83-7184-4678-bd45-6d0f3dedcf93)

#### Step 3: Training
This part is quite simple. You can find a detailed explanation in the colab file I shared above.

#### Step 4: Evaluating
1- Confusion Matrix:
![confusion_matrix](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/7377f265-85e9-4d9d-9e15-464abb3ae959)
2- Graphs:
![loss_graphs](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/2c833829-fe3a-4b6b-bddd-0845e66b69b4)
3- Image Results:

![result1](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/ae51bf2a-0ac5-4c82-acf6-d443b9e203d4)
![result2](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/366019ea-7d15-4f54-8798-4705978a1d2a)

According to these results, we can say that our model is quite successful.

### Final Result

![final_video](https://github.com/FikretOguzhan/YOLOv8_Football_Player_Detection/assets/85081014/336d45df-fb90-46da-992f-93a96efc573f)




