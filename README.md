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

### 3. Download required python files and Create dataset hierarchy. 


- Download Yolo cfg file and edit it according it to your own needs.
Edit : 

	*Training*
	
	*batch=1*
  
	*subdivisions=16*
  
	*max_batches = 6000 (class = 1,2,3 if classes > 3 then each class  x 2000 )*
  
	*policy=steps*
  
	*steps=4800,5400 (steps is 80% and 90% max_batches )*
  
	*filters = 18 ( no. of class + 5 ) x 3*
  
	*classes=1*

- Download create_train.py and create_test.py
- Create this hierarchy in your local system.
![image](https://user-images.githubusercontent.com/86966248/197758148-31415571-a89b-4fd4-93f9-8f3888a42657.png)


-  Create yolov4 folder in Google drive.
![image](https://user-images.githubusercontent.com/86966248/197758073-377772ae-66e7-49af-9791-c059d1ee3a22.png)
