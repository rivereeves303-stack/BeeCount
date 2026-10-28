# BeeCount Personal Fork

这是基于开源项目 BeeCount 的个人维护版本，主要用于 Android 本地离线记账。

## 我的修改

- 历史备注按当前分类筛选
- 适配当前 Android / Flutter 构建环境
- 主要保留本地记账相关功能

## 使用说明

当前主要面向 Android 平台使用。

构建正式 APK：

```powershell
flutter build apk --release --flavor prod
```

arm64-v8a 设备可安装：

```text
app-arm64-v8a-prod-release.apk
```

## 上游项目

本项目基于：

TNT-Likely/BeeCount

进行个人修改和维护。

## 许可证

本项目保留原项目的许可证和版权说明，请参阅仓库中的 `LICENSE` 文件。