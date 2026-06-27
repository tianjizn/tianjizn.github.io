# Gento Skye+Luna

## 概述

Gento 产品线包括 Gento Skye 和 Gento Luna 人形机器人，使用 **SDK 04** 版本。

## 仓库地址

**GitHub**: [tianji-robot-SDK](https://github.com/tianjizn/tianji-robot-SDK)

**分支**: `Gento_Skye+Luna`

## 快速开始

### 1. 克隆仓库

```bash
git clone -b Gento_Skye+Luna git@github.com:tianjizn/tianji-robot-SDK.git
```

### 2. 目录结构

```
tianji-robot-SDK/
├── README.md              # 项目文档
├── C_SDK/                # C SDK 源码
├── C_EXAMPLE/            # C 示例代码
├── PYTHON_SDK/           # Python SDK
├── PYTHON_EXAMPLE/       # Python 示例
├── FX_PLATFORM/          # 平台工具
└── linux_auto_compile.sh # Linux 编译脚本
```

### 3. Python 示例

```python
from GentoRobot import Robot

robot = Robot()
robot.connect("192.168.1.100")
state = robot.get_state()
print(state)
```

### 4. C++ 编译

```bash
./linux_auto_compile.sh
```

## 固件要求

- **必须使用 04 版本固件**
- 固件版本不匹配可能导致功能异常

## 摇操文档

请访问 [KLM Motion 文档中心](https://klmmotion.github.io/Apex_doc_center/) 查看摇操部分相关操作说明。
