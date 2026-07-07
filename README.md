# TVBox 海信电视专用版本

海信电视封锁了 TVBox 原版包名 `com.github.tvbox.osc`，以下收集了适配海信电视的专用版本。

## 版本列表

| 版本 | 日期 | 来源 | 弹幕 | 推荐 |
|------|------|------|------|------|
| [20260227-1116](../../releases/tag/hisense-20260227) | 2026-02-27 | takagen99 fork | ✅ | ⭐ 推荐 |
| [20260213-0733](../../releases/tag/hisense-20260213) | 2026-02-13 | takagen99 fork | ✅ | |
| [20250217-1618](../../releases/tag/hisense-20250217) | 2025-02-17 | - | ❌ | |

## 说明

- **包名**: `com.github.hisense.osc.tk` (绕过海信封锁)
- **签名**: TVBoxOSC 官方证书 (兼容饭太硬等后台源的 spider 签名校验)
- **架构**: armeabi (兼容所有 ARM 设备)
- **弹幕**: 20260213 及之后的版本内置 DanmakuFlameMaster 弹幕引擎
- **播放器**: 新版本使用 Media3 (原 ExoPlayer) + 阿里云播放器

## 安装使用

1. 下载最新 Release 中的 APK 文件
2. 通过 U 盘或局域网安装到海信电视
3. 打开后配置后台地址即可使用

## 注意

- 这些 APK 仅适用于海信电视
- 使用饭太硬后台源时，需确保 APK 使用 TVBoxOSC 官方证书签名，否则 spider 会校验失败导致闪退
