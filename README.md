# 2D Geometric Coordinate System | 2D 几何坐标系

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## English

### Overview

An interactive 2D geometric coordinate system visualization tool with advanced mathematical and physics symmetry features. This web-based application provides a comprehensive environment for creating, manipulating, and analyzing geometric shapes with precise mathematical properties.

### ✨ Key Features

#### 🎨 Geometric Elements
- **Basic Shapes**: Points, Lines, Circles, Rectangles, Arcs
- **Advanced Curves**: Polygons, Bezier Curves, Ease Curves
- **Mathematical Functions**: Plot and visualize mathematical functions

#### 🔄 Transformation Operations
- **Rotation**: Rotate elements with precise angle control
- **Translation**: Move elements in 2D space
- **Reflection/Symmetry**: Mirror elements across axes with symmetry constraints

#### 🧮 Mathematical Features
- Real-time coordinate calculations
- Area and perimeter computations
- Angle measurements and conversions
- Distance calculations
- Geometric property analysis (centroids, bounding boxes, etc.)

#### 🎯 Advanced Capabilities
- **Local Symmetry Constraints**: Apply physics-based symmetry rules to geometric transformations
- **Observation Points**: Define and constrain observation points with local symmetry
- **Feature Points**: Identify special points (symmetric points, inflection points, singular points, corners)
- **Interactive Property Editor**: Real-time editing of element parameters

#### 🎛️ User Interface
- **Element Management Panel**: View and organize all geometric elements
- **Property Panel**: Edit element attributes with live preview
- **Drawing Tools Menu**: Quick access to drawing operations
- **Keyboard Shortcuts**: Efficient workflow with comprehensive hotkeys
- **Dark Mode**: Eye-friendly dark theme support
- **Bilingual Interface**: Full support for English and Chinese

#### 💾 Data Management
- **Export/Import**: Save and load projects in JSON format
- **Canvas Export**: Export visualizations as images
- **Undo/Redo**: Full action history support

### 🚀 Getting Started

1. **Open the Application**
   ```bash
   # Simply open axis.html in a modern web browser
   open axis.html
   ```

2. **Basic Operations**
   - **Left Click**: Select elements or start drawing
   - **Right Click**: Open drawing menu
   - **Scroll Wheel**: Zoom in/out
   - **Middle Click + Drag**: Pan the coordinate system
   - **Space + Left Drag**: Quick pan alternative

3. **Drawing Elements**
   - Right-click to open the drawing menu
   - Select the desired element type
   - Follow the on-screen prompts to complete the shape

4. **Editing Elements**
   - Select an element to view its properties
   - Use the property panel to modify parameters
   - Apply transformations through the transform menu

### ⌨️ Keyboard Shortcuts

| Key | Function |
|-----|----------|
| `Space + Drag` | Pan coordinate system |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + Y` | Redo |
| `Ctrl/Cmd + S` | Save project |
| `Delete` | Delete selected element |
| `Esc` | Cancel current operation |
| `?` | Show help dialog |
| `F` | Open function input dialog |
| `Alt` | Special drawing operations |

### 🛠️ Technical Features

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Canvas-based Rendering**: High-performance 2D graphics
- **Mathematical Precision**: Accurate geometric calculations
- **Responsive Design**: Adapts to different screen sizes
- **Cross-browser Compatible**: Works on modern browsers

### 📊 Supported Geometric Types

| Type | Description | Key Properties |
|------|-------------|----------------|
| Point | Single coordinate point | Position, size, style |
| Segment | Line segment | Start/end points, length, slope |
| Circle | Perfect circle | Center, radius, area, circumference |
| Rectangle | Rectangular shape | Corners, width, height, diagonal |
| Arc | Circular arc | Center, radius, start/end angles |
| Polygon | Multi-vertex shape | Vertices, perimeter, area |
| Bezier Curve | Bezier curve | Control points, curvature |
| Ease Curve | Easing function curve | Ease type, timing function |
| Function | Mathematical function | Expression, domain, range |

### 🎓 Use Cases

- **Education**: Teaching geometry and coordinate systems
- **Mathematics**: Visualizing mathematical concepts and theorems
- **Physics**: Demonstrating symmetry and transformation principles
- **Design**: Creating and analyzing geometric patterns
- **Research**: Exploring geometric properties and relationships

### 🤝 Contributing

Contributions are welcome! This project is designed to be educational and accessible.

### 📄 License

MIT License - See [LICENSE](LICENSE) file for details

### 🔗 Project Structure

```
axis/
├── axis.html          # Main application file (all-in-one)
├── README.md          # This file
└── LICENSE            # MIT License
```

### 💡 Tips

- Use the **right-click menu** for quick access to drawing tools
- Enable **dark mode** for comfortable viewing in low-light environments
- Leverage **local symmetry constraints** for physics-accurate transformations
- Use the **function dialog** (press `F`) to plot mathematical functions
- Export your work regularly to save progress

---

<a name="中文"></a>
## 中文

### 概述

一个交互式 2D 几何坐标系可视化工具，具有先进的数学和物理对称性特性。这个基于 Web 的应用程序为创建、操作和分析具有精确数学属性的几何图形提供了全面的环境。

### ✨ 核心功能

#### 🎨 几何元素
- **基础图形**：点、直线、圆形、矩形、弧线
- **高级曲线**：多边形、贝塞尔曲线、缓动曲线
- **数学函数**：绘制和可视化数学函数

#### 🔄 变换操作
- **旋转**：精确角度控制的旋转变换
- **平移**：在 2D 空间中移动元素
- **镜像/对称**：跨轴镜像元素，支持对称性约束

#### 🧮 数学特性
- 实时坐标计算
- 面积和周长计算
- 角度测量和转换
- 距离计算
- 几何属性分析（质心、边界框等）

#### 🎯 高级功能
- **局域对称性约束**：对几何变换应用基于物理的对称性规则
- **观测点**：定义和约束具有局域对称性的观测点
- **特征点**：识别特殊点（对称点、拐点、奇异点、角点）
- **交互式属性编辑器**：实时编辑元素参数

#### 🎛️ 用户界面
- **元素管理面板**：查看和组织所有几何元素
- **属性面板**：实时预览编辑元素属性
- **绘图工具菜单**：快速访问绘图操作
- **键盘快捷键**：全面的热键支持高效工作流
- **暗色模式**：护眼的暗色主题支持
- **双语界面**：完整支持中英文切换

#### 💾 数据管理
- **导出/导入**：以 JSON 格式保存和加载项目
- **画布导出**：将可视化内容导出为图像
- **撤销/重做**：完整的操作历史支持

### 🚀 快速开始

1. **打开应用程序**
   ```bash
   # 在现代网络浏览器中打开 axis.html
   open axis.html
   ```

2. **基本操作**
   - **左键单击**：选择元素或开始绘图
   - **右键单击**：打开绘图菜单
   - **滚轮**：缩放视图
   - **中键拖拽**：平移坐标系
   - **空格 + 左键拖拽**：快捷平移

3. **绘制元素**
   - 右键单击打开绘图菜单
   - 选择所需的元素类型
   - 按照屏幕提示完成图形绘制

4. **编辑元素**
   - 选择元素以查看其属性
   - 使用属性面板修改参数
   - 通过变换菜单应用变换操作

### ⌨️ 键盘快捷键

| 按键 | 功能 |
|-----|------|
| `空格 + 拖拽` | 平移坐标系 |
| `Ctrl/Cmd + Z` | 撤销 |
| `Ctrl/Cmd + Y` | 重做 |
| `Ctrl/Cmd + S` | 保存项目 |
| `Delete` | 删除选中元素 |
| `Esc` | 取消当前操作 |
| `?` | 显示帮助对话框 |
| `F` | 打开函数输入对话框 |
| `Alt` | 特殊绘图操作 |

### 🛠️ 技术特性

- **纯 HTML/CSS/JavaScript**：无外部依赖
- **基于 Canvas 渲染**：高性能 2D 图形
- **数学精度**：精确的几何计算
- **响应式设计**：适应不同屏幕尺寸
- **跨浏览器兼容**：支持现代浏览器

### 📊 支持的几何类型

| 类型 | 描述 | 主要属性 |
|------|------|----------|
| 点 | 单一坐标点 | 位置、大小、样式 |
| 线段 | 线段 | 起点/终点、长度、斜率 |
| 圆 | 完美圆形 | 圆心、半径、面积、周长 |
| 矩形 | 矩形形状 | 角点、宽度、高度、对角线 |
| 弧线 | 圆弧 | 圆心、半径、起始/结束角度 |
| 多边形 | 多顶点形状 | 顶点、周长、面积 |
| 贝塞尔曲线 | 贝塞尔曲线 | 控制点、曲率 |
| 缓动曲线 | 缓动函数曲线 | 缓动类型、时序函数 |
| 函数 | 数学函数 | 表达式、定义域、值域 |

### 🎓 应用场景

- **教育**：教授几何和坐标系统
- **数学**：可视化数学概念和定理
- **物理**：演示对称性和变换原理
- **设计**：创建和分析几何图案
- **研究**：探索几何属性和关系

### 🤝 贡献

欢迎贡献！本项目旨在具有教育性和可访问性。

### 📄 许可证

MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

### 🔗 项目结构

```
axis/
├── axis.html          # 主应用程序文件（一体化）
├── README.md          # 本文件
└── LICENSE            # MIT 许可证
```

### 💡 提示

- 使用**右键菜单**快速访问绘图工具
- 启用**暗色模式**以在弱光环境中舒适查看
- 利用**局域对称性约束**实现符合物理规律的变换
- 使用**函数对话框**（按 `F` 键）绘制数学函数
- 定期导出作品以保存进度

---

## 🌟 Star History

If you find this project helpful, please consider giving it a star! ⭐

如果您觉得这个项目有帮助，请考虑给它一个星！⭐
