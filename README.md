# 基于YOLOV5+DEEPSORT的无人机行人检测
1. **环境配置**： 按requirements.txt配置conda环境，注意yolov5的环境可能需要重新配置一下。
2. **模型**： yolov5文件夹下的weights中包含了训练完成的uav5s.pt模型，基于yolov5s框架训练而成。
3. **训练和检测方法**：instruction.md中包含了常用的指令，记得改一下权重，数据集等路径。

4. **数据集配置**：数据集文件夹名称为uav_human，解压缩后放置在yolo同级目录下即可。注意数据集里的yaml文件，需要把验证集和训练集的路径改为本机的路径。数据集链接放在了百度云中，链接如下：链接：https://pan.baidu.com/s/1B3eyFSfm96sinaePJtU4yw?pwd=cmnp 提取码：cmnp 

   原视频数据集为okutama-action，链接如下：http://okutama-action.org/

5. 该模型对无人机视频中的行人检测的最终性能指标为：71.5%(mAP@0.5)，以下提供了一个完整的demo：

   【基于YOLOv5的无人机行人检测--有DeepSort】 https://www.bilibili.com/video/BV1nM411E7oW/?share_source=copy_web&vd_source=b1680350b3e39b1c077ca9ac4d394dca
   
   【基于YOLOv5的无人机行人检测--无DeepSort】 https://www.bilibili.com/video/BV1Ey4y1o7Nn/?share_source=copy_web&vd_source=b1680350b3e39b1c077ca9ac4d394dca
