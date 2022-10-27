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

### 1.1. Classes in Dataset (Total 50 Indian Dishes , each class has 20 images )
1. Masala Dosa
2. Idli
3.  Parathas
4. Poha
5. Samosa
6. Chole Bature
7. Medhu Vada
8. Upma
9. Vada Pav
10. Momos
11.  Bombay Sandwich
12. Gobi Manchurian
13. Frankie
14. Ragada Pattice
15. Noodle Soup
16. Dahi Puri
17.  Kachori
18. Pani Puri
19. Dhokla
20. Pav Bhaji
21. Butter chicken
22. Tandoori chicken
23.  Chicken Tikka Masala
24. Biriyani
25. Chicken 65
26. Prawn Koliwada
27. Goan Crab Masala
28. Gulab Jamun
29. Gajar Ka Halwa
30. Jalebi
31. Mothichur Laduu
32. Ras Malai
33.  Mutter Paneer
34. Naan
35. Raita
36. Saag Paneer
37. Aloo tikki
38. Malabar fish curry
39. Baati
40.  curd rice
41. Mattar paneer
42. uttapam
43. Aluchya wadya
44. Shrikhand
45. Kaju katli
46. Paneer tikka
47. Roti
48. Modak
49. Misal pav
50. Bhelpuri

### 2. Data Annotation.
Here is a list of tools that you can use for annotating images:

1.  [MakeSense.AI](https://www.makesense.ai/)  **( which i used for this Project )**
2.  [LabelImg](https://github.com/tzutalin/labelImg)
3.  [VGG image annotator](https://gitlab.com/vgg/via)
4.  [LabelMe](http://labelme.csail.mit.edu/Release3.0/)
5.  [Scalable](https://scalabel.ai/)
6.  [RectLabel](https://rectlabel.com/)
