# ClassIsland-LFG

受 Apple Liquid Glass 设计语言启发的 ClassIsland 玻璃质感主题。

## 特性

- 玻璃质感背景与高光叠层
- **多色边缘跑马灯效果**：彩虹色灯泡沿岛屿边缘顺时针流转，距离边缘约 1mm，7 色渐变流光
- 支持完整模式与精简（无通知）模式

## 安装

将 `dev.lladlam.lfg` 文件夹复制到 ClassIsland 的主题目录即可。

也可以从 [Releases](https://github.com/lladlam/ClassIsland-Theme-LFG/releases) 下载 `Liquid-Flavored-Glass.zip`，解压后得到 `dev.lladlam.lfg` 文件夹。

## 预览

![banner](dev.lladlam.lfg/banner.png)

## 构建

本项目为纯 XAML 主题，无需编译即可使用。如需生成可分发的 zip 包，可使用 GitHub Actions 工作流（`.github/workflows/build.yml`）：

- 推到 `main`/`master` 分支或创建 `v*` 标签时会自动打包
- 工作流同时兼容未来可能出现的 C# 项目（检测到 `.csproj` 时会先执行 `dotnet build`）

## 参考

ClassIsland自带Fluent
