# Salmon Factory Design - Interactive Web Application

## 项目概述 | Project Overview

这是一个交互式网页应用，展示年产 20000 吨三文鱼加工厂的完整设计方案。网页包含工厂布局、生产流程、物料计算、设备配置等详细信息，采用现代化的用户界面和交互设计。

This is an interactive web application showcasing a complete design 方案 for a 20,000-ton annual capacity salmon processing plant. The website includes detailed information on factory layout, production processes, material calculations, and equipment configuration, featuring a modern user interface and interactive design.

## 主要功能 | Key Features

### 核心功能 | Core Features



* **工厂概览** - 展示年产能、车间数量等关键数据

* **车间详情** - 6 个专业生产车间的详细信息

* **工艺流程** - 完整的三文鱼加工流程展示

* **物料计算** - 精确的物料平衡和能量消耗分析

* **设备配置** - 国际先进设备清单和投资估算

* **Factory Overview** - Display of key data such as annual capacity and number of workshops

* **Workshop Details** - Comprehensive information on 6 specialized production workshops

* **Process Flow** - Complete salmon processing workflow visualization

* **Material Calculations** - Precise material balance and energy consumption analysis

* **Equipment Configuration** - International advanced equipment list and investment estimation

### 交互特性 | Interactive Features



* **点击式详情查看** - 点击车间获取详细信息

* **数据可视化** - Chart.js 图表展示关键数据

* **响应式设计** - 适配桌面端和移动端

* **动画效果** - 平滑过渡和悬停动画

* **Click-to-view Details** - Click workshops for detailed information

* **Data Visualization** - Chart.js charts displaying key metrics

* **Responsive Design** - Optimized for desktop and mobile devices

* **Animation Effects** - Smooth transitions and hover animations

## 技术栈 | Technology Stack

### 前端技术 | Frontend Technologies



* **HTML5** - 语义化网页结构

* **CSS3** - 层叠样式表

* **JavaScript** - 交互功能实现

* **Tailwind CSS v3** - 现代化 CSS 框架

* **Font Awesome** - 图标库

* **Chart.js** - 数据可视化库

* **HTML5** - Semantic web structure

* **CSS3** - Cascading style sheets

* **JavaScript** - Interactive functionality implementation

* **Tailwind CSS v3** - Modern CSS framework

* **Font Awesome** - Icon library

* **Chart.js** - Data visualization library

## 项目结构 | Project Structure



```
salmon-factory-design/

├── index.html              # 主页面文件 | Main HTML file

├── README.md              # 项目说明文档 | Project documentation

└── assets/                # 资源文件目录 | Asset directory

&#x20;   ├── images/           # 图片资源 | Image resources

&#x20;   └── icons/            # 图标文件 | Icon files
```

## 使用说明 | Usage Instructions

### 快速开始 | Quick Start



1. **本地运行** - 直接打开 index.html 文件

2. **在线访问** - 部署到 Web 服务器或使用静态网站托管服务

3. **移动设备** - 支持响应式设计，可在手机和平板上访问

4. **Local Run** - Open the index.html file directly

5. **Online Access** - Deploy to web server or use static website hosting service

6. **Mobile Devices** - Responsive design supports mobile and tablet access

### 交互操作 | Interactive Operations



* **点击车间** - 查看详细的车间信息和工艺流程

* **导航菜单** - 使用顶部导航跳转到不同功能区域

* **图表交互** - 悬停查看图表详细数据

* **模态框操作** - 点击关闭按钮或外部区域关闭详情窗口

* **Click Workshops** - View detailed workshop information and processes

* **Navigation Menu** - Use top navigation to jump to different functional areas

* **Chart Interaction** - Hover to view detailed chart data

* **Modal Operations** - Click close button or outside area to close detail windows

## 技术特性 | Technical Specifications

### 设计特点 | Design Features



* **现代化 UI** - 采用海洋主题配色方案

* **响应式布局** - 适配各种屏幕尺寸

* **动画效果** - CSS3 动画和 JavaScript 交互

* **数据可视化** - Chart.js 实现的专业图表

* **Modern UI** - Ocean-themed color scheme

* **Responsive Layout** - Adapts to various screen sizes

* **Animation Effects** - CSS3 animations and JavaScript interactions

* **Data Visualization** - Professional charts implemented with Chart.js

### 性能优化 | Performance Optimization



* **轻量级设计** - 最小化外部依赖

* **快速加载** - 优化的代码结构和资源加载

* **SEO 友好** - 语义化 HTML 结构

* **无障碍访问** - 符合 WCAG 标准的设计

* **Lightweight Design** - Minimal external dependencies

* **Fast Loading** - Optimized code structure and resource loading

* **SEO Friendly** - Semantic HTML structure

* **Accessibility** - WCAG-compliant design

## 应用场景 | Application Scenarios

### 目标用户 | Target Users



* **食品加工企业** - 工厂设计参考和方案展示

* **投资决策者** - 项目评估和投资分析

* **技术人员** - 工艺学习和设备选型

* **学生教育** - 水产加工专业教学参考

* **Food Processing Enterprises** - Factory design reference and scheme presentation

* **Investment Decision-makers** - Project evaluation and investment analysis

* **Technical Personnel** - Process learning and equipment selection

* **Education** - Reference for aquatic product processing education

### 商业价值 | Business Value



* **方案展示** - 专业的工厂设计方案展示平台

* **技术交流** - 促进行业内技术经验分享

* **投资分析** - 提供项目投资决策参考

* **市场推广** - 企业技术实力展示工具

* **Scheme Presentation** - Professional factory design showcase platform

* **Technical Exchange** - Promoting industry technology and experience sharing

* **Investment Analysis** - Providing reference for project investment decisions

* **Marketing** - Tool for demonstrating enterprise technical capabilities

## 开发指南 | Development Guide

### 环境要求 | Environment Requirements



* **浏览器支持** - Chrome, Firefox, Safari, Edge 等现代浏览器

* **开发工具** - VS Code, WebStorm 等代码编辑器

* **版本控制** - Git (推荐)

* **Browser Support** - Chrome, Firefox, Safari, Edge and other modern browsers

* **Development Tools** - VS Code, WebStorm and other code editors

* **Version Control** - Git (recommended)

### 自定义修改 | Customization Guide

#### 颜色主题 | Color Theme

修改 Tailwind CSS 配置文件中的颜色变量：



```
tailwind.config = {

&#x20;   theme: {

&#x20;       extend: {

&#x20;           colors: {

&#x20;               primary: '#0EA5E9',

&#x20;               secondary: '#06B6D4',

&#x20;               accent: '#F59E0B',

&#x20;               ocean: '#0891B2',

&#x20;               fish: '#F97316'

&#x20;           }

&#x20;       }

&#x20;   }

}
```

#### 数据更新 | Data Updates

修改 JavaScript 中的工厂数据配置：



```
const workshopData = {

&#x20;   fresh: {

&#x20;       title: '冰鲜车间',

&#x20;       capacity: '4,000吨/年',

&#x20;       // 其他配置...

&#x20;   },

&#x20;   // 其他车间数据...

};
```

#### 图表配置 | Chart Configuration

调整 Chart.js 图表参数：



```
new Chart(ctx, {

&#x20;   type: 'doughnut',

&#x20;   data: {

&#x20;       labels: \['冰鲜车间', '冷冻车间', '切片车间', '罐头车间', '鱼肉松车间', '熏鱼车间'],

&#x20;       datasets: \[{

&#x20;           data: \[4000, 4000, 2000, 3000, 4000, 3000],

&#x20;           backgroundColor: \[

&#x20;               '#10B981', '#06B6D4', '#8B5CF6', '#EF4444', '#F59E0B', '#F97316'

&#x20;           ]

&#x20;       }]

&#x20;   }

});
```

## 部署说明 | Deployment Instructions

### 本地部署 | Local Deployment



1. 下载项目文件到本地

2. 直接打开 index.html 文件

3. 使用浏览器开发工具查看效果

4. Download project files to local machine

5. Open index.html file directly

6. Use browser developer tools to view 效果

### 服务器部署 | Server Deployment



1. 将所有文件上传到 Web 服务器

2. 确保服务器支持静态文件访问

3. 配置适当的 MIME 类型

4. 访问域名查看网站

5. Upload all files to web server

6. Ensure server supports static file access

7. Configure appropriate MIME types

8. Access domain name to view website

### 静态托管 | Static Hosting

推荐使用以下平台进行静态网站托管：



* **Netlify** - 全球 CDN，自动部署

* **Vercel** - 快速部署，预览功能

* **GitHub Pages** - Git 仓库直接部署

* **AWS S3** - 云存储静态网站托管

Recommended platforms for static website hosting:



* **Netlify** - Global CDN with automatic deployment

* **Vercel** - Fast deployment with preview 功能

* **GitHub Pages** - Direct deployment from Git repository

* **AWS S3** - Cloud storage static website hosting

## 技术支持 | Technical Support

### 常见问题 | Frequently Asked Questions

**Q: 网页在移动设备上显示异常怎么办？**

**A: 检查是否正确使用了响应式设计类，确保 meta viewport 标签配置正确。**

**Q: Charts are not displaying correctly, what should I do?**

**A: Check Chart.js library loading and ensure canvas elements have proper dimensions.**

**Q: 如何添加新的车间或修改现有数据？**

**A: 修改 JavaScript 中的 workshopData 对象，添加或更新相应的车间配置。**

**Q: How to add new workshops or modify existing data?**

**A: Modify the workshopData object in JavaScript to add or update workshop configurations.**

### 联系方式 | Contact Information

如需技术支持或合作洽谈，请通过以下方式联系：

For technical support or cooperation inquiries, please contact us through:



* **项目邮箱** - project@salmonfactory.com

* **技术文档** - [https://docs.salmonfactory.com](https://docs.salmonfactory.com)

* **在线演示** - [https://demo.salmonfactory.com](https://demo.salmonfactory.com)

## 许可证 | License

本项目采用 MIT 许可证，详情请参考 LICENSE 文件。

This project is licensed under the MIT License, please refer to the LICENSE file for details.

## 更新日志 | Changelog

### v1.0.0 (2025-10-23)



* 初始版本发布

* 完整的工厂设计展示

* 6 个专业车间详情

* 物料计算和设备配置

* 响应式设计和交互功能

### v1.0.0 (2025-10-23)



* Initial version release

* Complete factory design showcase

* 6 specialized workshop details

* Material calculations and equipment configuration

* Responsive design and interactive features

## 致谢 | Acknowledgements

感谢以下项目和资源的支持：

Thanks to the following projects and resources for their support:



* **Tailwind CSS** - 现代化 CSS 框架

* **Font Awesome** - 图标库

* **Chart.js** - 数据可视化库

* **所有贡献者** - 为项目提供帮助的开发者

* **Tailwind CSS** - Modern CSS framework

* **Font Awesome** - Icon library

* **Chart.js** - Data visualization library

* **All Contributors** - Developers who helped with the project
