# 安装指南

## 环境要求

### 系统要求
- 操作系统：Windows/Linux/MacOS
- Python版本：3.10+
- 内存：建议12GB以上
- 存储空间：10GB以上

### 必需组件
- Git
- Python 3.10+
- pip包管理器
- Visual Studio 2022 C++桌面开发环境
- NVIDIA显卡驱动（CUDA）

### 安装步骤

#### Windows

软件下载：  
夸克网盘：[https://pan.quark.cn/s/66f5d7a386fb](https://pan.quark.cn/s/66f5d7a386fb) 提取码：HU8s  
迅雷网盘：[https://pan.xunlei.com/s/VOElCQaY1AOv9YzMqC97C9OeA1](https://pan.xunlei.com/s/VOElCQaY1AOv9YzMqC97C9OeA1) 提取码：q8py  
百度网盘：[https://pan.baidu.com/s/1kHNwVOmWPISar2XLnzLpLQ?pwd=atb7](https://pan.baidu.com/s/1kHNwVOmWPISar2XLnzLpLQ?pwd=atb7) 提取码: atb7  

试用密钥联系作者  



#### Linux

暂不提供，请联系作者

#### Mac OS

暂不提供，请联系作者

## 配置说明

### 基础配置

- `server`: 服务器配置
  - `host`: 监听地址
  - `port`: 监听端口

### 平台配置

需要在Web界面配置各平台的接入信息：

1. 抖音直播
   - 需要配置抖音开放平台的相关参数
   - WebSocket服务器地址

2. 快手直播
   - 快手开放平台的接入参数
   - 相关密钥配置

3. 哔哩哔哩直播
   - 账号Cookie信息
   - 直播间ID

### 模型配置

1. 大语言模型
   - OpenAI API密钥
   - 其他模型的接口地址和认证信息

2. 语音合成
   - 各TTS引擎的接口地址
   - 模型路径配置

## 常见问题

### 1. 启动失败
- 检查端口是否被占用
- 查看日志文件排查错误
- 确认配置文件格式正确

### 2. 无法访问Web界面
- 检查防火墙设置
- 确认服务器IP和端口配置
- 查看服务运行状态

## 升级指南

下载最新版整合包，替换data文件夹即可。（具体根据官方公告操作升级）
