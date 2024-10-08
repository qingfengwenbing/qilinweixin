# 麒麟微信接口

## 项目简介

本项目是一个基于 Tkinter 和 ttkbootstrap 的桌面应用程序，实现了一个简单的微信机器人功能。用户需要通过购买的激活码进行登录，登录成功后，系统将启动微信机器人，并通过 WebSocket 与客户端进行通信。

### 项目特点
- **数据加密**：采用 Fernet 对用户数据进行加密存储，确保信息安全。
- **微信机器人**：集成微信消息处理，支持处理文本消息、图片消息等功能。
- **WebSocket 通信**：通过 WebSocket 服务端与客户端实时通信，处理微信消息和响应。

## 目录结构

```bash
├── _internal/                 # 内部数据存储文件
├── 微信日志.log                 # 微信日志文件
├──麒麟微信接口.exe                 # 主程序文件
