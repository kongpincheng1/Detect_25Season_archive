# 说明
这是25赛季仿真视觉代码的存档，删去了其他无用的代码。<br>
仿真运行的程序为`detect_ros_sim_lowHz.py`

```bash
ros2 run detect test
```

# 注意
使用前请根据自己计算机的路径修改`detect_ros_sim_lowHz.py`中权重文件`best_sim.pt`的路径,`best_sim.pt`已经给出，这是yolov8适用于仿真环境的模型，后续如果有需要可自行训练其他。<br>
同时也请适当修改`detect_ros_sim_lowHz.py`中`video_output_path`的路径，这可以将每次的画面录像保存到特定路径，你可以将它关掉。

## 这个ros2包的名称为detect

## 可用的setuptools版本 pip install setuptools==58.0.4

>**祝你好运**