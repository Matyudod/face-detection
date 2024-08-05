# Face Detection using Multi-task Cascaded Convolutional Networks (MTCNN)

MTCNN (Multi-task Cascaded Convolutional Neural Network) is a deep learning-based approach for face detection and facial landmark localization. It's a popular and efficient method known for its accuracy.   

MTCNN operates in a cascaded manner, consisting of three stages:

1. Proposal Network (P-Net): This stage scans the image to generate potential face candidates. It uses a convolutional neural network (CNN) to quickly filter out non-face regions.   
2. Refine Network (R-Net): The second stage refines the bounding boxes generated by the first stage, improving their accuracy and eliminating false positives.   
3. Output Network (O-Net): This final stage aims to describe the face in more detail and output the five facial landmarks’ positions for eyes, nose and mouth.

## Build with 2 environments
We will help 2 environments to for each Notebooks


### With "fd-use-lib.ipynb" we will use "req.txt" requirement file.
#### Create Env
```
    python -m venv venv
```
#### Setup environment
```
    venv\Scripts\activate
    pip install -r req.txt -q
```
#### run fd-use-lib.ipynb
- Select the Kernal
- Choose "venv" environment
- Run all


### With "fd-from-scraft.ipynb" we will use "req1.txt" requirement file.
#### Create Env
```
    python -m venv venv1
```
#### Setup environment
```
    venv1\Scripts\activate
    pip install -r req1.txt -q
```
#### run fd-use-lib.ipynb
- Select the Kernal
- Choose "venv1" environment
- Run all

## Reference
1. https://github.com/timesler/facenet-pytorch