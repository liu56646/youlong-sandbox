# 游龙沙箱 (Youlong Sandbox)

在 Android 手机上运行另一个 Android 系统的全虚拟化沙箱（自研 AOSP QEMU + ranchu，纯 TCG，**无需 root**）。

## 下载

- **安装包（推荐，已内置国内加速）**：[youlong-sandbox-0.1.0-debug.apk](https://gh-proxy.org/https://github.com/liu56646/youlong-sandbox/releases/latest/download/youlong-sandbox-0.1.0-debug.apk)
- 直连备用：[GitHub 直链](https://github.com/liu56646/youlong-sandbox/releases/latest/download/youlong-sandbox-0.1.0-debug.apk)

访客镜像 p11_arm64.zip **无需手动下载**，App 会自动经 gh-proxy.org 加速获取。

## 使用

1. 安装 APK
2. 打开后点「一键启动」
3. 首次会下载约 500MB 镜像，随后自动启动访客系统

## 支持范围

| 项 | 要求 |
|---|---|
| ABI | arm64-v8a |
| Android | 9.0 (API 28) + |
| 内存 | 建议 6GB+ |
| 存储 | 需 6GB+ 空闲 |
| root | 不需要 |

## 已知限制

- 纯软件模拟（TCG）：首次启动约 10–15 分钟，运行画面约 5 FPS
- 目前仅提供 Android 11 访客镜像
- 请勿在运行期间把 App 切后台过久：部分机型会冻结进程导致访客暂停
