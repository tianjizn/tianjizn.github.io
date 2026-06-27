# Marvin Pro

## 概述

Marvin Pro 是天机机器人的人形机器人产品，使用 **SDK 03** 版本。

## 仓库地址

**GitHub**: [tianji-robot-SDK03](https://github.com/tianjizn/tianji-robot-SDK03)

**分支**: `Marvin_Pro`

## 快速开始

### 1. 克隆仓库

```bash
git clone -b Marvin_Pro git@github.com:tianjizn/tianji-robot-SDK03.git
```

### 2. 目录结构

```
tianji-robot-SDK03/
├── README.md              # 项目文档
├── contrlSDK100343/     # 控制 SDK
├── kinematicsSDK/        # 运动学 SDK
├── SDK_PYTHON/          # Python SDK
├── DEMO_C++/            # C++ 示例代码
├── DEMO_PYTHON/        # Python 示例代码
├── CommonConfig/        # 配置文件
├── MarvinPlatform_EN/   # 平台软件
└── marvinSDK_ubuntu_100343.sh  # Linux 编译脚本
```

### 3. Python 示例

```python
import fx_robot

robot = fx_robot.Robot()
robot.connect("192.168.1.100")
state = robot.get_state()
print(state)
```

### 4. C++ 编译

```bash
./marvinSDK_ubuntu_100343.sh
```

## 固件要求

- **必须使用 03 版本固件**
- 固件版本不匹配可能导致功能异常

## 摇操文档

请访问 [KLM Motion 文档中心](https://klmmotion.github.io/Apex_doc_center/) 查看摇操部分相关操作说明。
