# EmoNexa 🎵
#### Emotion Based Music Player

### Emotion Dectector

<p> It is a facial emotion recognition system that operates in two modes: training and real-time emotion detection. In training mode, it employs a convolutional neural network (CNN) built with Keras to recognize facial expressions such as anger and happiness. The script utilizes OpenCV for capturing video frames, and Haar cascades for face detection in real-time emotion recognition mode. Detected faces are processed through the pre-trained CNN, which predicts emotions in real-time and overlays corresponding labels onto the video feed. The trained model achieves an accuracy of 63.2%. </p>

#### running it....

```bash
python emotions.py --mode train
```

To view the predictions without training again run:  

```bash
python emotions.py --mode display
```

Link to Dataset: [FER2013](https://www.kaggle.com/datasets/deadskull7/fer2013/)
<br>
Link to Refrence Paper: [Challenges in Representation Learning: A report
on three machine learning contests](https://arxiv.org/pdf/1307.0414.pdf)

##### Accuracy has to be improved, exploring other techniques

### Music Classifier

##### Need to be worked upon

### Concusion

<p> The project is current in it's initial stage and there is a lot to be added </p>
