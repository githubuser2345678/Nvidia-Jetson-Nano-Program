# Nvidia-Jetson-Nano-Program
 My dataset: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/discussion/300481

https://vscode-remote+ssh-002dremote-002b192-002e168-002e137-002e145.vscode-resource.vscode-cdn.net/home/nvidia/jetson-inference/python/training/classification/test2.png?version%3D1723210914389
 
My project identifies over 42 different German traffic signs using machine learning.

I created this program by taking the data above and training a resnet-18 AI to classify the signs.  You can run this program with the following commands.

DATASET=data/whatSign

NET=models/whatSign

imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/(filename).png (output filename).png

This will be helpful for people traveling to germany and unfamiliar with the road signs, or visually impaired people in germany

*contains no malware*

Video


https://drive.google.com/file/d/1UCuLmp3DCvZNAj-2ILry_gQk4uWqPie9/view?usp=drive_link
