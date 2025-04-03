# 优创智绘（上海）计算机科技服务有限公司官网

这是优创智绘（上海）计算机科技服务有限公司的官方网站项目。

## 项目结构

```
.
├── images/           # 图片目录
│   ├── logo.png     # 公司logo
│   └── banner.jpg   # 网站banner图片
├── css/
│   ├── tailwind.css  # Tailwind CSS 源文件
│   └── styles.css    # 编译后的 CSS 文件
├── index.html        # 首页
├── works.html        # 作品展示页
├── create_images.html # 用于创建图片的工具
├── package.json      # 项目依赖
├── tailwind.config.js # Tailwind 配置
└── README.md         # 项目说明
```

## 图片处理

由于GitHub Pages的限制，外部图片链接可能无法正常显示。为了解决这个问题，我们提供了以下解决方案：

1. 使用 `create_images.html` 工具创建简单的占位图片：
   - 打开 `create_images.html` 文件
   - 点击"下载Logo"和"下载Banner"按钮
   - 将下载的图片保存到 `images` 目录中

2. 或者，您可以使用自己的图片：
   - 将您的logo图片命名为 `logo.png` 并保存到 `images` 目录
   - 将您的banner图片命名为 `banner.jpg` 并保存到 `images` 目录

## 安装依赖

```bash
npm install
```

## 开发

```bash
# 监视 CSS 变化并自动编译
npm run watch:css
```

## 构建

```bash
# 构建并压缩 CSS
npm run build:css
```

## 部署

将整个项目上传到GitHub仓库，然后启用GitHub Pages功能即可部署网站。

## 技术栈

- HTML5
- Tailwind CSS
- JavaScript 