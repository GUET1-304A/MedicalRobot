# 医疗服务机器人 MedicalRobot

## 📋 项目简介

本项目致力于实现面向医疗场景的服务型机器人应用，支持引领、定位、语音交互、导航、充电等多种业务功能。通过集成先进的人工智能技术和机器人控制系统，为医疗机构提供智能化、自动化的服务解决方案。

**This project aims to create a service robot application for medical scenarios, supporting leading, positioning, voice interaction, navigation, charging, and more.**

## ✨ 核心功能

- 🎤 **语音交互与控制** - Voice Interaction & Control  
  支持自然语言对话，智能语音指令识别与执行

- 🗺️ **自动导航与路径规划** - Auto Navigation & Path Planning  
  智能避障、动态路径规划、多点导航

- 👥 **引领服务** - Leading Service  
  患者引领、科室引导、智能跟随

- 📍 **定位与地图管理** - Positioning & Map Management  
  高精度室内定位、地图构建与管理

- 🔋 **充电自动化** - Charging Automation  
  低电量自动返回充电、智能电量管理

- 🚪 **门控/电动门集成** - Electric Door Integration  
  自动门控制、无障碍通行

- 🎮 **运动控制** - Basic Sports Control  
  精确的移动控制、姿态调整

- 👁️ **视觉识别** - Vision Processing  
  人脸识别、物体检测、环境感知

## 🛠️ 技术栈

- **开发环境**: Android Studio
- **开发语言**: Java (JDK 1.8)
- **平台要求**: 定制 Android 系统
- **核心依赖**: 
  - Android SDK
  - 机器人厂商 CoreService/SDK
  - 第三方集成库

## 📦 环境要求

### 软件要求
- Android Studio (最新稳定版)
- JDK 1.8 (Java 8)
- Android SDK
- Git

### 硬件要求
- 基于定制 Android 系统的机器人设备
- 支持语音交互、导航、视觉识别等功能的机器人硬件平台

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/GUET1-304A/MedicalRobot.git
cd MedicalRobot
```

### 2. 导入项目

1. 打开 Android Studio
2. 选择 `File` → `Open`
3. 选择克隆的项目目录
4. 等待 Gradle 同步完成

### 3. 配置环境

1. 确保 JDK 1.8 已正确配置
2. 配置 Android SDK 路径
3. 根据机器人厂商文档配置 CoreService/SDK

### 4. 构建项目

```bash
# 使用 Gradle 构建
./gradlew assembleDebug

# 或在 Android Studio 中
# Build → Build Bundle(s) / APK(s) → Build APK(s)
```

### 5. 部署运行

**推荐方式**：手动在机器人设备上启动 App 以获取必要的系统权限

1. 将生成的 APK 文件传输到机器人设备
2. 在机器人屏幕上手动安装并启动应用
3. 授予应用所需的权限（定位、麦克风、摄像头等）

## 📱 应用场景

- 🏥 **医院导诊** - 患者引导、科室指引
- 💊 **药品配送** - 自动化药品运输
- 📋 **信息查询** - 医疗信息咨询、挂号指导
- 🔍 **病房巡检** - 自动化病房巡视
- 📦 **物资运输** - 医疗物资配送

## 🔧 配置说明

项目配置文件位于 `/app/src/main/` 目录下，主要配置项包括：

- **网络配置**: API 接口地址、超时设置
- **机器人参数**: 运动速度、导航精度
- **语音配置**: 语音识别引擎、TTS 设置
- **地图配置**: 地图文件路径、定位参数

## 📖 项目结构

```
MedicalRobot/
├── app/                    # 主应用模块
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/      # Java 源代码
│   │   │   ├── res/       # 资源文件
│   │   │   └── AndroidManifest.xml
│   └── build.gradle
├── docs/                   # 项目文档
├── gradle/                 # Gradle 配置
├── build.gradle           # 项目构建配置
└── README.md              # 项目说明文档
```

## 🤝 贡献指南

我们欢迎所有形式的贡献！如果你想为项目做出贡献：

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📄 开源协议

本项目采用 MIT 协议开源，详见 [LICENSE](LICENSE) 文件。

## 👥 团队

GUET1-304A Team

## 📞 联系方式

- 项目主页: [https://github.com/GUET1-304A/MedicalRobot](https://github.com/GUET1-304A/MedicalRobot)
- 问题反馈: [Issues](https://github.com/GUET1-304A/MedicalRobot/issues)

## 🙏 致谢

感谢所有为本项目做出贡献的开发者和支持者！

---

⭐ 如果这个项目对你有帮助，请给我们一个 Star！
