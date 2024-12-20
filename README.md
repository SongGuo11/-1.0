# 图片元数据编辑器

一个用于查看、编辑和清除图片元数据的 Python 工具，支持单文件处理和批量处理。

## 功能特点

- 🖼️ 支持多种图片格式（JPEG、PNG、GIF、BMP）
- 📝 查看和编辑图片元数据（EXIF信息）
- 🧹 清除图片元数据
- 📱 内置多种手机型号的元数据预设
- 📏 调整图片尺寸和裁剪
- 🔄 批量处理功能
- 💾 支持保存无元数据副本

## 下载和使用

### 方式一：直接使用（推荐）
1. 在 [Releases](https://github.com/你的用户名/image-metadata-editor/releases) 页面下载最新版本
2. 解压后直接运行 `图片元数据编辑器.exe`

### 方式二：从源码运行
1. 克隆仓库：
   ```bash
   git clone https://github.com/你的用户名/image-metadata-editor.git
   ```
2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```
3. 运行程序：
   ```bash
   python image_metadata_editor_gui.py
   ```

### 方式三：自行打包
1. 安装依赖
2. 运行 `build.py`
3. 在 dist 目录找到生成的可执行文件

## 使用方法

### 方式一：直接运行源码

1. 安装依赖：