# anti-boss-pro
use your pc to detect faces from your back

*主要是用笔记本自带的相机检测人脸,程序入口 faced.py,请注意本程序主要是在docker中启动的，使用前需要先在系统中安装docker  
>执行
>docker pull dawsonenjoy/face_recognition

>执行
>docker run --privileged --device=/dev/video0:/dev/video0 -v $PWD:/tmp -w /tmp faced:v1 python3 faced.py
