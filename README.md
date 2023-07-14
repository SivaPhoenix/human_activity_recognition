# human_activity_recognition
Human Activity Recognition using ML

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
