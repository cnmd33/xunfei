# Bag 文件分析

## 话题

- `/driver/encoder`: 包含 `nav_msgs/Odometry` 消息，表示编码器数据。
- `/driver/eul`: 包含 `sensor_msgs/Imu` 消息，表示欧拉角数据。
- `/driver/imu`: 包含 `sensor_msgs/Imu` 消息，表示惯性测量单元数据。
- `/driver/mag`: 包含 `sensor_msgs/MagneticField` 消息，表示磁场数据。
- `/driver/scan`: 包含 `sensor_msgs/LaserScan` 消息，表示激光扫描数据。

## 数据属性

- `nav_msgs/Odometry`: 包含位置和速度信息。
- `sensor_msgs/Imu`: 包含线性加速度和角速度信息。
- `sensor_msgs/MagneticField`: 包含磁场强度信息。
- `sensor_msgs/LaserScan`: 包含激光扫描数据。

## 示例

### 播放 bag 文件

```bash
rosbag play [jiantu2.bag](http://_vscodecontentref_/0)