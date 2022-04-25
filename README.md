# FACE-MASK-NAMES-DETECTION-AND-KEEPING-POSTED-THEM-TO-WEAR-MASK

In this project, we are going to build an algorithm such that the person who ever enters without wearing a mask will be sorted in real-time and the algorithm detects his face from organization data and his name will be shouted loudly and alerts him to wear his mask.

requirements:
python, cuda, cudnn

Steps:
1. Firstly, we capture images of persons each of 50 images for more accuracy (CaptureDataset.py)
2. Then we train the captured faces (train_faceDetector.py)
3. We collect the dataset of persons with and without mask 
get it from: https://drive.google.com/drive/folders/1VxIffbvxbt7g5xqYyO7BhWQrjFwcMhMU?usp=sharing
4. we train the mask data (train_maskDetector.ipynb)
this method produced more heat and more processing power
5.we run the main file

Demo:
![video](https://user-images.githubusercontent.com/83135144/165171658-a72fb335-77ae-4359-a203-20c62b2ed7cb.gif)
