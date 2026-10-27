# 人体图谱 · 中文版（Human Atlas CN）

基于 [ashemag/human-atlas](https://github.com/ashemag/human-atlas) 的中文汉化版，通过 GitHub Actions 打包为 Android APK 与 iOS IPA。

- 界面全中文（系统名 / 说明 / 错误提示 / 关于页）
- 支持中文搜索常用名（心脏、股骨、膈肌…）
- 解剖模型数据（BodyParts3D，CC BY 4.0）在构建时从上游仓库拉取并打进安装包，**离线可用**

## 构建产物

进入 **Actions** 页面选择一次运行，在 Artifacts 中下载：

- `human-atlas-android-apk` —— 直接安装（允许未知来源）
- `human-atlas-ios-ipa` —— 未签名，用 Sideloadly / AltStore 签名后安装，或有 Apple 开发者账号直接签名分发

原始应用代码 MIT License；解剖数据 © The Database Center for Life Science, CC BY 4.0。
