# Car-Type-detection

# 1. Objective 
The goal of this project was to train a YOLOv4 Darknet model for detecting and classifying four car types: Sedan, 
SUV, Hatchback, and Taxi
# 2. Dataset Creation
- Source: The dataset was obtained from public sources containing images of cars, YouTube Videos Extraction with 
the target classes: Sedan, SUV, Hatchback, and Taxi.
- Annotation Tool: By using labelimg manual annotation for the car was done
- Data count : all 4 type classes mixed images were 2830 and their annotated files
  
![image](https://github.com/user-attachments/assets/647722ed-1eb3-40e6-8cc0-6333c31ebca1)

# 3. Preprocessing 
- Data uploading : uploading the images 
and their annatatoted files into drive 
- Training Environment: Training was 
conducted using Google Colab for ease 
of GPU access and cost efficiency.
- Cloning the darknet repository into 
Colab , required packages and 
mounting the drive And compiling 
- Data Splits: The dataset was split into 
training (80%), validation (10%), and test 
(10%) sets.
- Creating the data.obj ,data.name,
train.txt, test.txt, val.txt files
- Modifying cfg file their names , batch sizes, max iteration ,layers and downloading the weights
![image](https://github.com/user-attachments/assets/f7e697da-cac9-4cd0-b5b8-0fc9c554dd31)
# 4 Aurgementation 
![image](https://github.com/user-attachments/assets/48730a9c-9d95-4234-a86f-afb49f41e611)
# 5 Training
This process included the model trained again on the data the train images are 3892 
o These images were undergone though the process of training
o As the batch size is more the training process going fast Map are also high
![image](https://github.com/user-attachments/assets/34ae4c0a-b2b8-4829-ac25-cd02400be6e1)
![image](https://github.com/user-attachments/assets/da67a4e2-a087-4948-8a75-671de6d46f38)
# 6 Weights
![image](https://github.com/user-attachments/assets/266d3fd8-0a49-4139-845a-b66167928b6a)
# 7 testing
![image](https://github.com/user-attachments/assets/4b5b55bf-cfb1-463f-acfc-bb166d6762c0)
![image](https://github.com/user-attachments/assets/989dd550-d27c-4e3e-adbb-90e788c5d6d5)






