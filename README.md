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
