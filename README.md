# Object detection 

### Algorithm used : Yolo algorithm
### Backend : opencv
### Library required:

- opencv = 4.5.4-dev'


# Quick Overview about structure

#### 1) main.py

- Loading model and user configurations
- show detected objected


#### 2) yolo.py

- use opencv modules to detect objects from user given media(photo/video)
- detection take place inside this file


#### 3) config.json

- user configuration are mentioned inside this file
- for examples : input shapes and model parameters(weights file path , config file path etc) are added in config.json


# How to use 

1) clone this directory

2) use following command to run detection on your custom video

  ```
  python main.py -c config.json -v <media_path>
  ```

  Ex: 
  ```
  python main.py -c config.json -v car1.mp4
  ```


### Results
![detected_car1](https://user-images.githubusercontent.com/69752829/141614391-69e1ab6f-1382-4b0f-bc0d-f94b072e07fe.PNG)
![detected_car2](https://user-images.githubusercontent.com/69752829/141614399-16abb25c-f667-453c-b6ce-8226ca6a4f48.PNG)
![detected_car3](https://user-images.githubusercontent.com/69752829/141614402-fd6978d8-ef44-41c3-93f7-b3e028e29688.PNG)




