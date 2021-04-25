# GAN genereted face detection

Small research to build deep learning model to enable detected faces that generated by Generative Adversarial Network like StyleGan 2, check [This Person Does Not Exist](https://thispersondoesnotexist.com)
## Application

 [Source Code](/source/application)
### Used teckstack

* Model: tensorflow 2
* Backend: flask
* Client:  Vue.js
* Orchestration:  docker-compose

### UI

![Demostration](/description_images/Animation.gif)

### Build and run

        cd source/
        
        docker-compose build

        docker-compose up

        open http://localhost:8082


## Training

[Notebook](/source/notebooks/NovemberFirst_CustomDataset.ipynb)
### Datasets

[1-million-fake-faces](https://www.kaggle.com/c/deepfake-detection-challenge/discussion/121173)

[flickrfaceshq-dataset-nvidia-resized-256px](https://www.kaggle.com/xhlulu/flickrfaceshq-dataset-nvidia-resized-256px)

[140k-real-and-fake-faces](https://www.kaggle.com/xhlulu/140k-real-and-fake-faces)

[real-and-fake-face-detection](https://www.kaggle.com/ciplab/real-and-fake-face-detection)




### Classification model architecture
![Architecture](/description_images/architecture.png)

## Confusion matrix
![Confusion matrix](/description_images/classification_matrix.png)


## Evaluation
### Right classification
![Right classification](/description_images/right_clasification.png)

### True positive
![True positive](/description_images/wrong_true_positive.png)

### False negative
![False negative](/description_images/wrong_false_negative.png)
