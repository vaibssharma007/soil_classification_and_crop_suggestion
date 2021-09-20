# Soil-Type-Classification for Crops Suggestion 🌳🌲

## Description
For this project i have trained a deep learning model with 903 images of four different types soil namely:-
1. Alluvial
2. Black
3. Clay 
4. Red 

All images are collected from Google Search Engine and crafted and filtered. It also suggests the type of crop we can grow on that particular soil. To implement this webapp we had used Flask (a framework of Python), which uses a convolution neural network on the back end to perform the above classification. Model is deployed on Heroku Platform (https://www.heroku.com/).


## Model deployed as Web-Application AP at:📳  <br>
https://classify-soil-crop-by-vaibhav.herokuapp.com/


## Dataset available at: 📚 <br>
The dataset used for training and evaluating the model: https://www.kaggle.com/omkargurav/soil-classification-image-data. The obtained model has achieved 99% accuracy on the test set.

## Model

![13](https://user-images.githubusercontent.com/91024630/133990855-f2a0e06d-a78b-4f5b-8712-c3b31d4512be.png)

The network itself was implemented using transfer learning. The MobileNet V2 model developed at Google was used as a base model for feature extraction from our data. A custom classification layer was added on top and trained separately. You can learn more about this approach here. The notebook I used to implement the model on Google Colab can be found [here](https://github.com/vaibssharma007/soil_classification_and_crop_suggestion/blob/main/Soil-Type-Classification-Soilnet%20(1).ipynb).


## Flow Chart :

![flow_chart](https://user-images.githubusercontent.com/91024630/133940541-008a5290-51d6-4f25-8514-caf8c37ac2d2.jpeg)


## Dependencies:
For this project, the following tools were used:

1. Tensorflow 2 for building and training the model
2. Numpy for working with arrays
3. Matplotlib for visualizing the data
4. Flask for implementing the server side
5. HTML5, CSS3, JavaScript (with Web Speech API and particles.js) on the front-end.

## IO Screenshots:📷 <br>

### This is the home page of our website :-

![1](https://user-images.githubusercontent.com/91024630/133939805-803419af-24ff-4125-ad5c-fd27fe9d17ef.png)
![2](https://user-images.githubusercontent.com/91024630/133939724-467ef740-2b3c-4952-b5a9-a3dad76badb3.png)
![3](https://user-images.githubusercontent.com/91024630/133939726-60feefbd-32c1-45ef-879f-229e25feeb28.png)
![4](https://user-images.githubusercontent.com/91024630/133939728-16635916-3f09-4166-bec3-3ddeaad89fb1.png)

### These are the predicted results after uploading pictures of different soils :-

![5](https://user-images.githubusercontent.com/91024630/133939732-47a5392e-679a-4447-a20c-41abb2fc7b8d.png)
![6](https://user-images.githubusercontent.com/91024630/133939735-1164b5d0-f973-4a05-adce-09775d531910.png)
![7](https://user-images.githubusercontent.com/91024630/133939743-156fff28-c86d-46cc-9577-d719cc2d50c3.png)
![8](https://user-images.githubusercontent.com/91024630/133939746-cdcc13dc-6d0c-4b5f-998e-13a2b50c9000.png)

### Credits:-
![9](https://user-images.githubusercontent.com/91024630/133939747-147877df-1b8d-493e-ae2f-3ac2649bcc26.png)


## Acknoledgement:🎓 <br>
I am expressing my gratitude towards Sir Krish Naik for his super clear explanation about Neural Network in Deep Learning Playlist(https://www.youtube.com/watch?v=DKSZHN7jftI&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi) and Model Deployment Tutorial(https://www.youtube.com/watch?reload=9&reload=9&reload=9&reload=9&v=Ie4-AOpPxBg&list=PLZoTAELRMXVPUyxuK8AphGMuIJHTyuWna)


