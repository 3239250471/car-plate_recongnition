# 车辆检测+车牌检测与识别 YOLO + LPRnet +CSPdark
#### 缺失权重文件，请至邮箱中下载
#### 介绍
环境安装
```
-  CUDA 10.0
- pip install torch===1.2.0 torchvision===0.4.0 -f https://download.pytorch.org/whl/torch_stable.html

-  CUDA 9.2
- pip install torch==1.2.0+cu92 torchvision==0.4.0+cu92 -f https://download.pytorch.org/whl/torch_stable.html

-  CPU only
- pip install torch==1.2.0+cpu torchvision==0.4.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
```


#### 使用说明
1. 在inference文件中的images文件夹下导入要识别的图片或者视频
2.  运行detect.py
3.  在/inference/output 路径下可看到输出情况
