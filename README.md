# India-Cuisine-Detection-using-YOLOv4
Create a custom Objection End to End Computer Vision Model which can detect different Indian Cuisines using YOLOv4 

Contents :
1. Data Collection.
2. Data Annotation.
3. Download required python files and Create dataset hierarchy. 
4. Training YOLO Weights.
5. Create Python scripts to detect object in Images. 
6. Create Python scripts to detect object in Videos.  
7. Build GUI using Streamlit for Detection in Images. )
8. References  
9. Future Improvements 

### 1. Data Collection.
We have gathered 25 classes of Indian food Cuisine (20 images per class)
1. Masala Dosa 
2. Idli 
3.  Parathas 
4. Poha 
5. Samosa 
6. Chole Bature 
7. Medhu Vada 
8. Upma 
9. Vada Pav 
10.  Kachori 
11. Pani Puri 
12. Dhokla 
13. Pav Bhaji 
14. Butter chicken 
15. Biriyani 
16. Prawn Curry 
17. Gulab Jamun 
18. Jalebi 
19. Saag Paneer 
20. Malabar fish curry 
21. Baati 
22. Mattar paneer 
23. Paneer tikka 
24. Misal pav 
25. Bhelpuri 


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
