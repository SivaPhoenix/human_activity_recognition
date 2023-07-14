# HUMAN ACTIVITY RECOGNITION 
This project aims to develop a human activity recognition system using deep learning techniques, specifically the Residual Neural Network (ResNet) architecture. The system can analyze input data, such as sensor readings or video frames, and accurately classify the performed human activities.


The project utilizes a carefully curated dataset of labeled human activities. The dataset includes various activities like walking, running, sitting, standing, and other complex actions like playing sports or cooking. The dataset provides a diverse range of examples, enabling the model to learn and generalize well.

## DATASET

click [here](https://drive.google.com/drive/folders/1RE--P5n8SsHN4tHcnUwKj6iXv7BqtFLv?usp=drive_link) to download the dataset

## RUN THE PROJECT
```python
cd human_activity_recognition
#to run and download the output
python human_activity_recognition.py --model resnet-34_kinetics.onnx --classes action_recognition_kinetics.txt --input videos/example_activities.mp4 --gpu 1 --output output.mp4
#for only run the project
python recognise_human_activity.py
```

## RESULT

The project aims to achieve high accuracy and robustness in recognizing human activities. The results achieved on the evaluation metrics, as well as any comparative analysis with other approaches, will be detailed in this section

## LICENSE

This project is licensed under the MIT License.
