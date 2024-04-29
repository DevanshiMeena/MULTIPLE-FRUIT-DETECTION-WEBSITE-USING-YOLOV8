Welcome to Fruitify!!
Our project introduces a multifaceted approach to image detection and user interaction, 
focusing on the identification of various fruits within uploaded images and providing tailored 
recipes based on user preferences. Employing advanced image processing techniques and 
machine learning algorithms, our system swiftly detects and labels fruits within multiple 
images, offering users an intuitive interface for seamless interaction. Beyond fruit detection, 
our platform enhances user engagement through personalized recipe recommendations. By 
incorporating user preferences such as taste profiles, dietary restrictions, and meal 
preferences, our system curates customized recipe suggestions, ensuring a delightful 
culinary experience for every user. Furthermore, our platform facilitates user feedback, 
fostering continuous improvement and refinement of both detection algorithms and recipe 
recommendations.
For object detection, YOLO-V8 has been used, which is able to detect 1000 objects. The 
objects areapple 
orange
banana
grape
Features:
1. Multiple fruit detection 
2.Recipe Recommendation System
3.Feedback Form 
User Instruction:
1. User will upload an image from his/her computer by clicking on select image button:
 (a)The picture uploaded must be in correct format of .JPEG/.PNG/JPG.
 (b)The uploaded picture must be clicked against a clear background and proper lightening
 (c)User can upload the image of single fruit or multiple fruits.
 (d)The uploaded image should contain either apple, banana, grape, orange (currently).
2. The user will get the detected image of fruits by clicking on Predict.
3.When the user will click on result, it will give the names of the predicted fruits.
4.If the user wants to know the recipes of the predicted fruits, user can click on next.
5.When the user clicks on next button, he/she will be asked for his/her preference.
6.After clicking on next, the website will show recipes according to his/her preference.
7.The user will be asked for his/her feedback, for future modifications.
Requirements to be installed before running the website:
Anaconda
LabelImg tool
VS Code
Google Colaboratory
Ultralytics YOLOv8 
Flask
NodeJs 
MongoDB
