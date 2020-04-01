# anti-boss-pro
use your pc to detect faces from your back
主要是用笔记本自带的相机检测人脸
程序入口

faced.py

执行
docker run --privileged --device=/dev/video0:/dev/video0 -v $PWD:/tmp -w /tmp faced:v1 python3 faced.py
