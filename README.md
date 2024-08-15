# SmartBrite: 智能灯光控制系统

[![GitHub](https://img.shields.io/badge/GitHub-Project-blue)](https://github.com/yourusername/smartbrite)

## 项目简介

**SmartBrite** 是一款专为现代家庭设计的智能灯光控制系统，支持通过蓝牙连接至智能手机和平板电脑等移动设备进行控制。它允许用户轻松地调整房间内的灯光亮度、颜色以及定时开关等功能，从而创造舒适且个性化的照明体验。

## 特点

- **跨平台支持**：支持iOS和Android系统的移动设备，以及macOS和Windows的桌面客户端。
- **多设备管理**：可以同时控制多个灯光设备，并支持分组管理。
- **个性化设置**：用户可以根据个人喜好自定义场景模式，例如阅读模式、电影模式等。
- **节能高效**：通过智能调度算法减少不必要的能耗，有助于节能减排。
- **易于安装与配置**：用户友好的界面让设置变得简单快捷。

## 技术栈

- **前端**：React Native (移动应用) 和 React (桌面应用)
- **后端**：Node.js 作为服务器端逻辑处理
- **通信协议**：Bluetooth Low Energy (BLE) 用于设备间的无线通信





## 安装与运行

### 移动端

1. 克隆此仓库到本地。
2. 进入 `mobile` 文件夹。
3. 运行 `pnpm install` 来安装依赖。
4. 使用 `pnpm android` 或 `pnpm ios` 启动应用。

### 桌面端

1. 进入 `desktop` 文件夹。
2. 运行 `pnpm install` 来安装依赖。
3. 使用 `pnpm tauri dev` 启动桌面客户端。

## 贡献指南

欢迎贡献者加入本项目！如果您有任何改进想法、发现bug或是想添加新功能，请随时提交 pull request 或 issue。
