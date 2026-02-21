# Fun Stuff 项目

这是一个包含多种有趣HTML页面的项目，提供了各种交互效果、游戏和实用工具。

## 本地运行

由于项目是纯前端实现，您可以直接在本地运行：

1. 下载或克隆项目到本地
2. 直接使用浏览器打开 `index.html` 文件即可
3. 无需安装任何额外软件或依赖

## 项目结构

```
funnyshit/
├── index.html          # 主入口页面，导航至所有其他页面
├── 3d-rotation.html    # 3D旋转效果
├── canvas-animation.html # Canvas动画
├── particle-effect.html # 粒子效果
├── typing-effect.html  # 打字效果
├── mini-game.html      # 迷你游戏
├── puzzle-game.html    # 拼图游戏
├── memory-game.html    # 记忆游戏
├── scientific-calculator.html # 科学计算器
├── unit-converter.html # 单位和汇率换算
├── latex-renderer.html # LaTeX公式渲染
└── README.md           # 项目说明文件
```

## 功能模块介绍

### 1. 3D旋转效果 (3d-rotation.html)
- 展示了CSS 3D变换效果
- 实现了一个可旋转的3D立方体
- 包含多种不同形状的3D效果

### 2. Canvas动画 (canvas-animation.html)
- 使用HTML5 Canvas API创建动态动画效果
- 实现了彩色粒子的随机运动
- 具有响应式设计，适配不同屏幕尺寸

### 3. 粒子效果 (particle-effect.html)
- 实现了基于Canvas的粒子系统
- 粒子具有物理运动特性
- 可交互的粒子效果

### 4. 打字效果 (typing-effect.html)
- 模拟打字机效果的文字动画
- 包含多种文字展示样式
- 具有响应式设计

### 5. 迷你游戏 (mini-game.html)
- 实现了一个简单的方块移动游戏
- 包含游戏规则和计分系统
- 具有响应式设计

### 6. 拼图游戏 (puzzle-game.html)
- 实现了一个可自定义难度的拼图游戏
- 支持4x4、5x5、6x6三种难度级别
- 具有游戏状态提示和完成检测
- 修复了拼图块图案重复的问题
- 修复了右侧空白区域的问题

### 7. 记忆游戏 (memory-game.html)
- 实现了经典的记忆配对游戏
- 包含游戏计时和计分系统
- 具有响应式设计

### 8. 科学计算器 (scientific-calculator.html)
- 实现了一个功能完整的科学计算器
- 支持基本算术运算、三角函数、对数函数等
- 具有预计算功能，实时显示计算结果
- 支持使用上一次计算结果进行新的运算

### 9. 单位和汇率换算 (unit-converter.html)
- 实现了长度、重量、温度和货币的单位换算
- 包含多种常用单位的转换
- 修复了汇率换算方向的问题

### 10. LaTeX公式渲染 (latex-renderer.html)
- 实现了基于MathJax的LaTeX公式渲染
- 支持常用LaTeX数学公式语法
- 提供了常用公式示例
- 修复了公式渲染错误的问题

## 技术栈

- HTML5
- CSS3 (包括CSS Grid、Flexbox、3D变换等)
- JavaScript (包括ES6+特性)
- HTML5 Canvas API
- MathJax (用于LaTeX渲染)

## 项目特点

- 所有页面均为纯前端实现，无需后端服务
- 响应式设计，适配不同屏幕尺寸
- 模块化结构，易于维护和扩展
- 代码注释详细，便于理解
- 界面美观，交互友好

## 注意事项

- 部分功能可能需要现代浏览器支持
- 汇率换算中的汇率为固定值，可能与实时汇率有差异
- 科学计算器的三角函数使用弧度制计算

## 浏览器兼容性

- 推荐使用Chrome、Firefox、Safari等现代浏览器
- 不保证在IE浏览器中的兼容性

## 贡献

欢迎提交问题和改进建议！

## 许可证

本项目为个人学习和娱乐目的创建，可自由使用和修改。