# 孢子花园 · Spore Garden

一个用 Canvas 绘制的互动粒子花园。移动鼠标或点击屏幕，种下会呼吸的光。

![HTML](https://img.shields.io/badge/HTML-single--file-e34f26?logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-8fffc0)

## 简介

「孢子花园」是一个单文件 HTML 交互实验。指针划过或点击时，会在画布上生成发光孢子粒子。粒子之间会自动连线，并随时间缓慢消散，形成一片不断生长、呼吸、凋零的光之花园。

## 效果

- 鼠标移动 → 持续种下少量孢子
- 鼠标点击 → 一次种下 18 个孢子
- 粒子之间距离小于 90px 时自动连线
- 粒子颜色在青绿到蓝紫之间随机
- 粒子会轻微漂浮、闪烁、逐渐透明消失
- 当粒子少于 20 个时，会自动在随机位置补充

## 使用

直接用浏览器打开 `index.html` 即可。无需构建、无需依赖、无需服务器。

```bash
git clone https://github.com/你的用户名/你的仓库名.git
cd 你的仓库名
open index.html   # macOS
# 或
start index.html  # Windows
