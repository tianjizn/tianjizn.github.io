# 快速开始

## 环境要求

- Python 3.8+ 或 C++ 编译器
- 网络连接（用于连接机器人）

## Python SDK 使用步骤

### 1. 安装依赖

```bash
pip install fx-robot
```

### 2. 连接机器人

```python
from fx_robot import Robot

robot = Robot()
robot.connect("192.168.1.100")  # 机器人 IP 地址
```

### 3. 获取机器人状态

```python
state = robot.get_state()
print(f"关节位置: {state.joint_positions}")
```

## C++ SDK 使用步骤

### 1. 下载 SDK

从 GitHub 仓库下载对应版本的 SDK。

### 2. 编译

```bash
./marvinSDK_ubuntu_100343.sh
```

### 3. 示例代码

参考  文件夹中的示例程序。

## 下一步

- 查看 [SDK 概述](sdk/overview)
- 查看 [完整 API 文档](sdk/download)

