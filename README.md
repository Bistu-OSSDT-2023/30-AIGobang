# PyGobangVS五子棋人机对战游戏（带有UI界面）

> 这是一个使用Python语言编写的五子棋（Gomoku）游戏，具有图形用户界面（UI），可以让玩家与计算机进行对战，并以可视化的方式展示游戏的进行。

## 游戏界面截图

### v1.0：

![0b7f9c4a8da44d542041e8ffacb432e](C:\Users\白\AppData\Local\Temp\WeChat Files\0b7f9c4a8da44d542041e8ffacb432e.png)![e8692f527ef61cdb9441ab58b9c10c2](C:\Users\白\AppData\Local\Temp\WeChat Files\e8692f527ef61cdb9441ab58b9c10c2.png)![b01ad33e53248c94d953dc1c42798e8](C:\Users\白\AppData\Local\Temp\WeChat Files\b01ad33e53248c94d953dc1c42798e8.png)



### v2.0:

![image-20230705112106622](C:\Users\白\AppData\Roaming\Typora\typora-user-images\image-20230705112106622.png)![image-20230705112114168](C:\Users\白\AppData\Roaming\Typora\typora-user-images\image-20230705112114168.png)![image-20230705112121641](C:\Users\白\AppData\Roaming\Typora\typora-user-images\image-20230705112121641.png)

## 游戏规则

五子棋是一款在方格棋盘上进行的两人游戏。玩家轮流在棋盘交叉点上落子（通常是黑白两色），目标是先在横、竖或斜线上连续地放置五个棋子。

## 游戏特点

提供图形用户界面，使游戏更直观和易于操作。
支持玩家与计算机的人机对战模式。
实现智能算法用于检测获胜的落子，并宣布胜利者。
提供游戏完成后重新开始的选项。
在控制台返回棋子落点的坐标。

## 先决条件

Python 3.x
Pygame环境

## 安装和运行

### 克隆仓库：

git clone https://github.com/YourUsername/Gomoku-Game.git

### 进入项目目录：

cd 

### 安装依赖：

pip install -r requirements.txt

> 注：确保您已安装Python包管理工具（pip）。

### 运行游戏：

python PyGobangVS 1.0.py（或python PyGobangVS 2.0.py）

## 游戏流程

运行游戏后，将显示一个包含游戏棋盘的窗口。

玩家（执黑子）和计算机（执白子）将轮流进行落子。

单击空白位置以落子。您可以使用鼠标左键来放置您的棋子。

游戏将自动检测胜利的落子，并宣布获胜者。

游戏结束后，您可以选择重新开始游戏或退出。

## 自定义设置

您可以通过修改PyGobangVS 1.0.py(或PyGobangVS 2.0.py）文件中的变量来调整棋盘大小和棋子外观等。
您还可以自定义游戏界面的外观和风格。

## 贡献

欢迎贡献！如果您发现任何问题或对改进有建议，请随时创建问题或提交拉取请求。

## License

本项目基于 MIT许可证 发布。