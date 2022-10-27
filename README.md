# India-Cuisine-Detection-using-YOLOv4
Create a custom Objection End to End Computer Vision Model which can detect different Indian Cuisines using YOLOv4 

Contents :
1. Data Collection.
2. Data Annotation.
3. Download required python files and Create dataset hierarchy. 
4. Training YOLO Weights.
5. Create Python scripts to detect object in Images. (See code : detection_in_images.py)
6. Create Python scripts to detect object in Videos. (See code : detection_in_videos.py)  
7. Build GUI using Streamlit for Detection in Images. (See code : app_images.py)
8. References  
9. Future Improvements 

### 1. Data Collection.

We will look at 5 such ways of collecting data for training your custom model that solves your problem.

- Publicly available open labelled datasets.
eg : ImageNet , COCO , Google's Open Image etc.
- **Scraping the Web ( which i used for this Project )**
- Taking Photographs.
- Data Augmentation.
- Data Generation ( Synthetic Data by GANs )

### 2. Data Annotation.
Here is a list of tools that you can use for annotating images:

1.  [MakeSense.AI](https://www.makesense.ai/)  **( which i used for this Project )**
2.  [LabelImg](https://github.com/tzutalin/labelImg)
3.  [VGG image annotator](https://gitlab.com/vgg/via)
4.  [LabelMe](http://labelme.csail.mit.edu/Release3.0/)
5.  [Scalable](https://scalabel.ai/)
6.  [RectLabel](https://rectlabel.com/)
