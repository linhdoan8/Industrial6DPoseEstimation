# How to run

Step 1: Clone this repo into your laptop/PC

Step 2: `cd Industrial6DPoseEstimation`

Step 3: 

Download dataset from link (https://files.slack.com/files-pri/TEL7B5P29-F01D610RAH3/download/doube-augmented.zip) and put inside this repo

Download pre-train model and put inside `backup` folder

Step 4: Build and run docker as below

`sudo docker build --network=host -t sspe .`

`sudo docker run -it --rm --network=host sspe 3dbox.data yolo-pose.cfg backup/init.weights`


