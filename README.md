## Flower Detection with YOLOv5
This is my first deep learning project using YOLOv5. In this project I made deep learning model to detect 2 kind of flower in my house yard. There are 2 types of flowers (hortesia and mavavicus). In total I used 104 images that I took and labelled by my self.

## Framework Used
- [PyTorch](https://pytorch.org/hub/ultralytics_yolov5/)
- [YOLOv5](https://ultralytics.com/yolov5)
- [Google Colab](https://colab.research.google.com/)
- [RoboFlow](https://roboflow.com/)
- [LabelImg](https://tzutalin.github.io/labelImg/)

## Installation
### To train YOLOv5 model using my dataset
```
coming soon
```

### To run my model
- Clone the YOLOv5 repository by [Ultralitics](https://ultralytics.com/)
```
git clone git@github.com:ultralytics/yolov5.git
```
- Open the yolov5 directory using IDE or code editor and setup the Python environment (I used Python 3.8 and Pycharm Professional Edition as my Python IDE)
- Get ready with all of the Python librabry that required
```
pip install -r requirements.txt
```
- Download my weights and yaml file from dataset directory
- Put those files in the yolov5 directory in your local computer
- Run the detect.py file using my custom weights
```bash
python detect.py --weights flower_07042022.pt --source 0  # webcam
                                              img.jpg  # image
                                              vid.mp4  # video
                                              path/  # directory
                                              path/*.jpg  # glob
```
- Result file will saved at  `runs/detect` in yolov5 directory
