# 《人！你好！》Ren Nihao

金海豚游戏开发大赛参赛作品 · Godot 4 全栈开发

## 在线试玩（H5）

GitHub Pages 开启后访问：

**https://kommww31824.github.io/ren-nihao/**

> 首次加载约 120MB，请耐心等待。建议使用 Chrome / Edge。

## Windows 下载

请到本仓库 **[Releases](https://github.com/Kommww31824/ren-nihao/releases)** 下载 Windows 安装包 / 压缩包。

## 项目简介

- 引擎：Godot 4.x
- 类型：叙事互动 / AVG
- 程序：全栈（对话引擎、存档、UI、音频、Shader 特效等）

## 仓库结构

| 路径 | 说明 |
|------|------|
| `docs/` | Web（H5）导出，用于 GitHub Pages |
| `releases_staging/` | 本地暂存的 Windows / H5 压缩包（不推入 Git，改走 Releases） |

## 本地打开 H5

用任意静态服务器打开 `docs/`，例如：

```bash
cd docs
python -m http.server 8080
```

浏览器访问 `http://localhost:8080`
