# 🎡 WhirlWin - 幸运大转盘 (Wheel of Fortune)

[![GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=github)](https://suyp-slf.github.io/WheelOfFortune/)

WhirlWin 是一个基于 **HTML5 Canvas** 和 **JavaScript** 开发的高性能响应式幸运大转盘。它支持通过外部 **JSON** 文件轻松配置多个场景的奖项，非常适合用于年会抽奖、聚会决定或真心话大冒险。

## 🌐 在线演示
点击访问我的大转盘：[https://suyp-slf.github.io/WheelOfFortune/](https://suyp-slf.github.io/WheelOfFortune/)

## ✨ 项目特性
* **多配置支持**：支持多个转盘模式（如“中午吃啥”、“真心话大冒险”等）一键切换。
* **JSON 驱动**：无需修改核心代码，只需编辑 `config.json` 即可更新奖项和颜色。
* **物理仿真**：采用 `Cubic Ease-Out` 减速算法，模拟真实的物理旋转惯性。
* **响应式设计**：适配 PC 和 移动端（手机/平板）屏幕尺寸。
* **原生开发**：无需任何第三方库，极致轻量，加载飞快。

## 🛠️ 如何自定义奖项？
你只需要修改仓库根目录下的 `config.json` 文件。格式如下：

```json
"category_id": {
    "name": "转盘名称",
    "prizes": [
        { "text": "奖项1", "color": "#十六进制颜色" },
        { "text": "奖项2", "color": "#十六进制颜色" }
    ]
}
