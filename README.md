# 3D_point_cloud_data_processing_class_notes
## 激光雷达原理
## 激光雷达安装、标定与同步
1. 硬件选型
![Screenshot from 2022-01-12 14-07-44](https://user-images.githubusercontent.com/27469356/149073304-1a5cce32-04d6-40a7-9329-1f8478737a2e.png)

2. 激光雷达安装方式
3. 多传感器数据融合
![Screenshot from 2022-01-12 14-12-58](https://user-images.githubusercontent.com/27469356/149073874-1edc3b83-5772-4e6e-965b-b7bf11404e15.png)
4. 激光雷达系统方案
![Screenshot from 2022-01-12 14-29-57](https://user-images.githubusercontent.com/27469356/149075875-08ce6677-6961-47ae-9e63-db3b99c8f62d.png)

5. 多传感器标定：时间标定和空间标定

时间标定

空间标定：空间同步，统一坐标系，空间位置标定——平移量和旋转量（roll, pitch, yaw）

6. 软件部分：障碍物检测，障碍物分类识别，运动物体跟踪，高精度点云地图构建，高精度定位，可行驶区域识别

物体跟踪：估计运动物体的运动状态——运动方向、速度大小、加速度、角速度、运动轨迹

可行驶区域检测：路沿检测、车道线检测、地面检测、路面检测等

SLAM建图挑战：精度要求；大场景稳定性高；人工干预少

建图算法方案：图优化结合闭环检测；多传感器融合

重定位



