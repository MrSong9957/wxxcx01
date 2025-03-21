# uni-preset-vue 项目

基于 Vue3 的 UniApp 项目模板

## 特性
- 使用 Vue 3 组合式 API 开发
- 支持多平台编译（H5/微信小程序/支付宝小程序等）
- 集成 Vite 构建工具
- 包含基础 UniApp 配置

## 快速开始

### 安装依赖
```bash
npm install
```

### 开发模式
```bash
# H5 开发
npm run dev:h5

# 微信小程序开发
npm run dev:mp-weixin
```

### 生产构建
```bash
# H5 构建
npm run build:h5

# 微信小程序构建
npm run build:mp-weixin
```

## 项目结构
```
├── src/
│   ├── App.vue        # 应用入口
│   ├── main.js        # 主配置文件
│   ├── manifest.json  # 应用配置
│   ├── pages/         # 页面目录
│   └── static/        # 静态资源
├── vite.config.js     # Vite 配置
└── package.json       # 依赖管理

## 技术栈
- Vue 3
- Vite 4
- UniApp
- PostCSS