# 🎨 Sketch Studio (Web Edition)

> A high-performance, privacy-first photo-to-sketch converter running entirely in the browser.
> 一个基于 Web 技术的高性能、隐私优先的图片转素描工具。

## 📖 Introduction (简介)

**Sketch Studio** is a professional-grade image processing tool designed to convert raster images into artistic sketches. Unlike server-side solutions, this tool processes images locally using HTML5 Canvas API, ensuring zero latency and maximum privacy.

本项目是一个专业级的图像处理工具，旨在将普通照片转换为艺术素描。与云端工具不同，本项目完全基于 HTML5 Canvas 在本地运行，实现了零延迟处理，并确保用户图片绝不上传至服务器。

## 🚀 Key Features (核心特性)

* **⚡ O(1) Gaussian Blur**: Implements optimized box-blur approximation for consistent performance regardless of blur radius. (采用滑窗算法优化模糊处理，拒绝卡顿)
* **🔪 Laplacian Sharpening**: Enhanced edge detection for crisp, pencil-like strokes. (引入拉普拉斯算子锐化，线条更犀利)
* **🎛️ Non-Destructive Workflow**: 7+ adjustable parameters including contrast, gamma correction, and vignette. (全参数无损调节)
* **🎨 Artistic Presets**: One-click styles for Classic Pencil, Charcoal, Blueprint, and Colored Sketch. (内置大师级艺术预设)
* **🔒 Privacy First**: All calculations happen in your browser. Your photos never leave your device. (隐私安全，图片不离本地)

## 🛠️ Tech Stack (技术栈)

* **Core**: Vanilla JavaScript (ES6+)
* **Rendering**: HTML5 Canvas API
* **Style**: CSS3 (Responsive Grid Layout)
* **Deployment**: GitHub Pages

## 🎮 How to Use (如何使用)

1.  Visit the live demo: [Click Here](https://dongshuai-dog.github.io/sketch-studio/)
2.  **Upload**: Drag & drop an image or click the upload button.
3.  **Adjust**: Use the sidebar to tweak line width, darkness, and paper texture.
4.  **Explore**: Try different presets like "Blueprint" or "Charcoal".
5.  **Export**: Click "Export HD Image" to save your artwork.

## 📄 License

MIT License. Free for personal and educational use.
