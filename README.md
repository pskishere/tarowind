# Tarowind

基于Taro和Tailwind CSS构建的跨平台小程序项目。

## 技术栈

- [Taro](https://taro.jd.com/) - 京东凹凸实验室开发的多端统一开发框架
- [React](https://reactjs.org/) - 用户界面构建库
- [Redux](https://redux.js.org/) - JavaScript 状态容器
- [Tailwind CSS](https://tailwindcss.com/) - 实用优先的CSS框架
- [TypeScript](https://www.typescriptlang.org/) - JavaScript的超集

## 功能特性

- 跨平台支持：微信小程序、支付宝小程序、H5等多平台
- Tailwind CSS集成，支持使用Tailwind样式开发小程序
- 基于TypeScript，提供类型安全
- Redux状态管理集成

## 开发

```bash
# 安装依赖
yarn

# 开发微信小程序
yarn dev:weapp

# 开发H5
yarn dev:h5

# 其他平台
yarn dev:[platform]
```

## 构建

```bash
# 构建微信小程序
yarn build:weapp

# 构建H5
yarn build:h5

# 其他平台
yarn build:[platform]
```

## 项目结构

```
tarowind/
├── config/               # 项目配置
├── dist/                 # 编译后的文件
├── src/                  # 源代码
│   ├── components/       # 公共组件
│   ├── pages/            # 页面
│   ├── store/            # Redux 状态管理
│   ├── styles/           # 全局样式
│   ├── utils/            # 工具函数
│   ├── app.config.ts     # 应用配置
│   ├── app.scss          # 应用样式
│   ├── app.tsx           # 应用入口
│   └── index.html        # H5入口HTML
├── types/                # 类型定义
├── .gitignore            # Git忽略文件
├── babel.config.js       # Babel配置
├── package.json          # 项目依赖
├── postcss.config.js     # PostCSS配置
├── project.config.json   # 小程序项目配置
├── tailwind.config.js    # Tailwind配置
└── tsconfig.json         # TypeScript配置
``` 