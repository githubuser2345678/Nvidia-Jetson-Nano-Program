# Nvidia-Jetson-Nano-Program
 My dataset: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/discussion/300481

![image](https://github.com/user-attachments/assets/2f1719db-626e-4111-8158-2c0e5d19bc1b)

 
My project identifies over 42 different German traffic signs using machine learning.
I created this program by taking the data above and training a resnet-18 AI to classify the signs.  You can run this program with the following commands.
DATASET=data/whatSign
NET=models/whatSign
imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/(filename).png (output filename).png
This will be helpful for people traveling to germany and unfamiliar with the road signs, or visually impaired people in germany
*contains no malware*
Video
https://drive.google.com/file/d/1UCuLmp3DCvZNAj-2ILry_gQk4uWqPie9/view?usp=drive_link
