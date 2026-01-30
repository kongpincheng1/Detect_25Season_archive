# 说明
这是25赛季仿真视觉代码的存档，删去了其他无用的代码。

仿真运行的程序为`detect_ros_sim_lowHz.py`

这个ros2包的名称为detect

> *对代码进行修改后，请运行`colcon build`重新构建*

## 在工作空间根目录运行下面的代码即可运行程序
```bash
source install/setup.bash
ros2 run detect test
```

# 注意
1.程序运行的是视觉模型文件是`models`下的`best_sim.pt`,这是yolov8适用于仿真环境的模型，后续如果有需要可自行训练其他。

2.适当修改`detect_ros_sim_lowHz.py`中`video_output_path`的路径，这可以将每次的画面录像保存到特定路径，你可以将它关掉。

3.在`setup.py`中，设置的程序入口名称为`test`,你可以自行更改。



### 可用的setuptools版本 pip install setuptools==58.0.4

>**祝你好运**
