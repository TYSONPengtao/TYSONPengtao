<h1 align="center">你好，我是 TYSON Pengtao 👋</h1>

<p align="center">
  <a href="./README.md">English</a>
  ·
  <a href="./README.zh-CN.md"><strong>简体中文</strong></a>
</p>

<p align="center">
  <strong>数字孪生 · 人工智能 · 工程计算 · 自动化</strong>
</p>

<p align="center">
  我正在构建连接 <strong>3D 空间、实时数据、仿真分析与物理世界</strong> 的实用技术系统。
</p>

<p align="center">
  <a href="https://tysonpengtao.github.io">
    <img src="https://img.shields.io/badge/个人网站-tysonpengtao.github.io-111827?style=for-the-badge&logo=githubpages&logoColor=white" alt="个人网站" />
  </a>
  <a href="https://github.com/TYSONPengtao/Tao-Digital-Twin">
    <img src="https://img.shields.io/badge/当前项目-TAO%20Digital%20Twin-0f766e?style=for-the-badge&logo=threedotjs&logoColor=white" alt="TAO Digital Twin" />
  </a>
</p>

---

## 👨‍💻 关于我

我正在构建一个个人技术实验室，重点探索这些方向的交叉：

- 🏠 **数字孪生** —— 交互式 3D 空间、实时状态与物理设备控制
- 🤖 **人工智能** —— AI 辅助工作流、本地模型与实用自动化
- 🧭 **工程计算** —— 仿真、空间系统与技术可视化
- 🔌 **自动化与物联网** —— API、MQTT、ESP32 / STM32 与真实设备接入
- 📊 **数据可视化** —— 把复杂系统变成更容易理解和操作的界面

我的长期方向，是逐步构建能够连接以下环节的可复用系统：

```text
模型 → 数据 → 仿真 → 决策 → 物理动作
```

---

## 🚧 当前主项目

### [TAO Digital Twin](https://github.com/TYSONPengtao/Tao-Digital-Twin)

一个模块化数字孪生平台，目标是把 Web / Three.js 以及未来的 Unreal Engine 场景，与实时数据、环境仿真和真实物理设备连接起来。

当前开发内容包括：

- 可交互的 3D 住宅 Demo
- 8 个模拟智能家居设备
- React + TypeScript + React Three Fiber
- FastAPI 后端
- REST + WebSocket 实时通信
- 设备实体 ↔ 场景节点统一映射
- 房间温度 / 湿度 / 风速状态
- PET 热舒适分析
- 太阳位置分析
- 简化通风模拟
- 后续接入 Home Assistant / MQTT / ESP32

```text
Web / Three.js       Unreal Engine / VR / AR
       \                    /
        \                  /
         +---- TAO Core ---+
               |
      Device / State / Command / Event
               |
     +---------+---------+---------+
     |         |         |         |
Home Assistant MQTT    Modbus    OPC UA
     |         |         |         |
 Smart Home   ESP32    PLC/IO   Industrial
```

---

## 🧰 技术栈

### 前端与 3D

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### 后端与科学计算

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 工程、IoT 与未来集成

![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-18BCF2?style=flat-square&logo=homeassistant&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📌 重点项目

| 项目 | 说明 | 状态 |
| --- | --- | --- |
| **[TAO Digital Twin](https://github.com/TYSONPengtao/Tao-Digital-Twin)** | 面向实时设备、环境仿真与未来物理控制的 3D 数字孪生平台 | 🚧 开发中 |
| **[TAO Personal Technology Lab](https://github.com/TYSONPengtao/TYSONPengtao.github.io)** | 个人技术作品集与项目索引 | 🟢 在线 |

---

## 🌡️ 数字孪生研究方向

当前环境分析路径：

```text
真实 / 模拟设备
      ↓
   设备状态
      ↓
   房间环境
      ↓
温度 / 湿度 / 风速 / MRT
      ↓
   PET 热舒适
      ↓
   3D 数字孪生
```

下一阶段计划：

1. 稳定房间级环境状态
2. 把门窗加入气流开口模型
3. 建立基于压差 / 开口的通风模型
4. 接入真实天气与太阳辐射数据
5. 增加房间热平衡模型
6. 评估 EnergyPlus / CFD 集成
7. 接入 Home Assistant / MQTT / ESP32
8. 扩展到 Unreal Engine 与农业数字孪生

---

## 🧭 我在意的工程原则

- 先把 **框架做好，再增加功能复杂度**
- 让可视化层与硬件协议保持解耦
- 区分模拟状态、请求状态与物理确认状态
- 在合适的场景优先采用本地优先架构
- 把安全设计作为架构的一部分，而不是后补
- 把实验逐步沉淀成可复用工具和有文档的系统

---

## 🌐 链接

<p>
  <a href="https://tysonpengtao.github.io">🌍 个人网站</a><br/>
  <a href="https://github.com/TYSONPengtao/Tao-Digital-Twin">🏠 TAO Digital Twin</a><br/>
  <a href="https://github.com/TYSONPengtao">💻 GitHub 主页</a>
</p>

---

<p align="center">
  <sub>一次构建一个真正能用的系统。</sub>
</p>
