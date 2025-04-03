# 优创智绘（上海）计算机科技服务有限公司官网

这是优创智绘（上海）计算机科技服务有限公司的官方网站项目。

## 项目结构

```
.
├── css/
│   ├── tailwind.css  # Tailwind CSS 源文件
│   └── styles.css    # 编译后的 CSS 文件
├── index.html        # 首页
├── works.html        # 作品展示页
├── package.json      # 项目依赖
├── tailwind.config.js # Tailwind 配置
└── README.md         # 项目说明
```

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

构建完成后，将 `index.html`、`works.html` 和 `css/styles.css` 文件部署到服务器即可。

## 技术栈

- HTML5
- Tailwind CSS
- JavaScript 