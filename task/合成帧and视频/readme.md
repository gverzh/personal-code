# 说明：
任务为将MMA-Net模型输出的标注图片与对应未标注原图片合成为一帧，并将结果帧合成视频。

# 文件说明
| 文件 | 输入 | 输出 |
|--|--|--|
|图像叠加--测试.py | output-0000.jpg <br> 00000.jpg |  output.jpg|
|视频合成--测试.py | 0_Road014_Trim004_frames | vedio(原图大小) |
|图像叠加.py | 测试集数据：根据VIL100--》data.txt文件 | 叠加目录 |
|视频合成.py | 叠加目录 | vedio(1280*720) | 

# 1.图像叠加测试代码
图像叠加-测试.py

# 2. 多帧合成视频测试代码
视频合成-测试.py

# 1.图像叠加最终代码
图像叠加.py

# 2. 多帧合成视频最终代码
视频合成.py
