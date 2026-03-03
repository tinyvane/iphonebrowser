# iphonebrowser - iPhone/iOS 工具 - 项目规划

## 项目概述
包含 ApplePNG 相关的 iOS/iPhone 工具项目（C# 实现）。

---

## 2026-03-03 Claude 建议

### 关于 ApplePNG
ApplePNG 通常是指苹果设备上使用的优化 PNG 格式（CgBI 格式），与标准 PNG 不同，需要特殊解码。

### 应用场景
- 提取 iOS App 图标（.ipa 文件中的图片）
- iOS App 资源分析
- 处理苹果设备的截图/图片

### 现代替代方案
- Python `pypng` 或 `Pillow` 也可以处理 CgBI PNG
- macOS 下 Xcode 开发者工具自带相关功能
- 如无积极使用需求，归档处理
