# iOS 特效引擎 SDK 集成 Demo

本项目是 商汤科技 提供的 [**特效引擎 SDK**](https://www.sensetime.com/cn/product-detail?categoryId=51133623&gioNav=1) iOS 集成演示工程，旨在帮助开发者快速了解如何在 iOS 项目中集成与使用我们的特效引擎 SDK。您可以通过运行本 Demo，直观体验 SDK 提供的各类人脸特效、贴纸、美颜、滤镜等功能。

---

## 🚀 功能亮点

- 人脸检测与跟踪
- 美颜效果（磨皮、美白、瘦脸等）
- AR 贴纸/道具实时叠加
- 实时滤镜效果
- 视频流处理与渲染
- 高性能渲染支持（基于 OpenGL ES/Metal）

---

## 📱 环境要求

- Xcode 14 及以上
- iOS 13.0 及以上
- 真机运行（部分功能依赖相机与人脸识别）

---

## 🧩 SDK 集成说明

本项目已经完成对 SDK 的集成，您无需单独引入 SDK 依赖。

如果您需要在自己的项目中引入 SDK，请参考如下步骤：

1. 下载并解压 SDK 包
2. 将 SDK 文件（如 `.framework` / `.a` / 资源文件）拖入项目
3. 配置依赖库：
   - `AVFoundation`
   - `CoreMedia`
   - `CoreImage`
   - `Accelerate`
   - `Metal`（如使用 Metal 渲染）
4. 打开 `Build Settings`，添加必要的 `Other Linker Flags` 和路径设置（如 `-ObjC`）

> 如需详细接入文档以及授权license，请[**联系商务**](mailto:business@sensetime.com)

---

## 反馈
- 如果您在使用过程中有遇到什么问题，欢迎提交 [**issue**](https://github.com/mahaomeng/SenseMars-Effects-test/issues)。


