# Frontend Winter Training 2026

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-%E5%B7%B2%E5%AE%8C%E6%88%90-green)

**2026 年寒假前端基础实训代码仓库**

从零开始，用三天时间系统过一遍 Web 前端的三大基石：HTML 结构 → CSS 样式 → JavaScript 交互

</div>

---

## 项目简介

本仓库是 2026 年寒假期间的前端基础实训代码，按天组织学习内容，每天一个独立模块。所有示例代码均可直接在浏览器中打开运行，配合注释和笔记，适合作为前端入门的学习路径参考。

学习顺序遵循「结构 → 表现 → 行为」的 Web 标准三分层思想：

1. **Day 01 — HTML**：负责网页的骨架与语义化结构
2. **Day 02 — CSS**：负责网页的外观、动效与布局
3. **Day 03 — JavaScript**：负责网页的交互逻辑与数据处理

## 目录结构

```text
frontend-winter-training-2026
├── Day01/                 # HTML 基础
│   ├── 1-初识html.html
│   ├── 2-其他常见标签.html
│   ├── 3-图片和音视频标签.html
│   ├── 4-列表标签.html
│   ├── 5-表格.html
│   └── 6-表单.html
├── Day02/                 # CSS 样式与布局
│   ├── 1-CSS引入方式.html
│   ├── 2-CSS选择器.html
│   ├── 3-其他选择器.html
│   ├── 4-文本属性.html
│   ├── 5-字体属性.html
│   ├── 6-过渡.html
│   ├── 7-动画.html
│   ├── 8-动画案例.html
│   ├── 9-盒子属性.html
│   ├── 10-内容盒子.html
│   ├── 11-边框盒子.html
│   ├── 12-弹性盒.html
│   └── outer.css
└── Day03/                 # JavaScript 基础
    ├── 1-初识js.html
    ├── 1-初识js.js
    ├── 2-变量声明.js
    ├── 3-基本数据类型.js
    ├── 4-引用数据类型.js
    ├── 5-数组.js
    ├── 6-函数.js
    └── 笔记.txt
```

## 学习路线与知识点

### Day 01 — HTML 网页结构

| 文件 | 核心知识点 |
| --- | --- |
| 初识 HTML | HTML 文档基本结构、标签语法、注释、开发工具使用 |
| 其他常见标签 | 标题、段落、文本格式化、超链接、换行与分割线 |
| 图片和音视频标签 | `img` 图片引入、`audio` / `video` 音视频嵌入与常用属性 |
| 列表标签 | 无序列表、有序列表、自定义列表及其使用场景 |
| 表格 | `table` 结构、行列合并、表格语义化 |
| 表单 | `form`、常见表单控件（输入框、单选、复选、下拉、按钮） |

### Day 02 — CSS 样式与布局

| 文件 | 核心知识点 |
| --- | --- |
| CSS 引入方式 | 行内样式、内部样式、外部样式表三种引入方式对比 |
| CSS 选择器 | 基础选择器：标签、类、id、通配符 |
| 其他选择器 | 后代、子代、交集、并集、伪类选择器及优先级计算 |
| 文本属性 | 字体颜色、对齐、文本修饰、行高等排版属性 |
| 字体属性 | 字体系列、大小、粗细、复合写法 |
| 过渡 | `transition` 过渡效果的触发与属性配置 |
| 动画 | `animation` 关键帧动画的定义与应用 |
| 动画案例 | 综合运用过渡与动画完成交互效果 |
| 盒子属性 | 盒模型的组成：`content`、`padding`、`border`、`margin` |
| 内容盒子 / 边框盒子 | `box-sizing` 两种盒模型计算方式的区别与选用 |
| 弹性盒 | Flex 弹性布局：主轴对齐、侧轴对齐、伸缩比例 |

### Day 03 — JavaScript 基础

| 文件 | 核心知识点 |
| --- | --- |
| 初识 JS | JavaScript 简介、引入方式、与网页的交互 |
| 变量声明 | `var` / `let` / `const` 的区别与使用规范 |
| 基本数据类型 | Number、String、Boolean、Undefined、Null 与 `typeof` 检测 |
| 引用数据类型 | 对象与数组在内存中的存储差异、值传递与引用传递 |
| 数组 | 数组创建、遍历、常用方法与增删改查 |
| 函数 | 函数声明与调用、参数与返回值、作用域 |

## 如何运行

本仓库所有示例均为纯静态页面，无需安装任何依赖：

1. 克隆仓库到本地
   ```bash
   git clone https://github.com/z-dog-z/frontend-winter-training-2026.git
   ```
2. 直接用浏览器打开任意 `.html` 文件即可查看效果
3. 推荐使用 VS Code 配合 Live Server 插件打开，支持实时刷新

## 总结与收获

通过这次实训，搭建了完整的前端知识框架：

- 能够独立手写语义化的 HTML 页面结构
- 掌握了选择器、盒模型与 Flex 布局，可以还原常见页面排版
- 理解了 JS 的基本类型系统、数组与函数，为后续 Vue 框架学习打下基础

后续实战项目请移步：[vue-music-player-app](https://github.com/z-dog-z/vue-music-player-app)

---

<div align="center">

如果这个仓库对你有帮助，欢迎点一个 Star ⭐

</div>
