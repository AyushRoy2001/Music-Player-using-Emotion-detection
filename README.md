# Music-Player-using-Emotion-detection
Youtube music player using Emotion detection model
## *1. Output :zipper_mouth_face:*
- Emotion detection using open cv and model.<br/><br/>
![Screenshot (29)](https://user-images.githubusercontent.com/94052139/146066530-9af4c75d-0d19-4268-a675-c6b6be4856e0.png)<br/><br/>

- Youtube song recommended with the help of emotion detected by model.<br/><br/>
![Screenshot (28)](https://user-images.githubusercontent.com/94052139/146035507-4934a6c4-3fba-4491-a107-98cb8438412d.png)

Couldn't record as the default recorder of windows 10 was only recording a single application :disappointed_relieved:.
## *2. Description :thinking:*
  - I created Deep Learning Neural Network model for detecting emotion.<br/> 
  - Used CNN for the model and then used Open Cv for emotion detection on live webcam feed.
  - Used Cosine Similarity to find out distance of the 5 closest vectors from the input movie vector in this project.<br/>
  - Converted the frames of the webcam to grayscale and found out the REGION OF INTEREST using Cascades.<br/>
  - Used Haarcascades for detecting the faces and reduced the minimum neighbors to 2 for better detection.<br/>
  - Saved the model and weights for implementing it in main.py file.<br/>
 ## *3. Dataset*
  - The dataset was the fer2013 dataset.<br/>
  - The pixels I used as X and Y was the labels(encoded) and aplied train_test_split later.<br/>
  - Datasets taken from ![Logo](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white).<br/>
 ## *4. Used*
 ![Logo](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)
 ![Logo](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
 ![Logo](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
 ![Logo](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)
 ![Logo](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
 ![Logo](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)
 ![Logo](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
 ![Logo](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)
 ## *5. IDE*
 ![Logo](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)
 ## *5. Future Improvements :raised_eyebrow:*
 The model accuracy will be improved by increasing epochs and reducing batch size(it took me 10 hrs to train the model<br/>
 and expecting the improvements to take even longer).
 ## *6. Contributers :nerd_face:*
  - Ayush Roy<br/>
