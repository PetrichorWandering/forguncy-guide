# 格言格语

售前团队的文本资料汇集地，活字格技术方案的图书馆。

本工程基于 [vitepress](https://vitepress.dev/guide/what-is-vitepress) 构建。

## 环境依赖

- node 18+
- npm 
- Vue 3 + TypeScript + Vite

## 运行

1. 当前目录下，终端运行 `npm install`，安装项目所有依赖。
2. 依赖安装成功后，终端运行 `npm run docs:dev`，启动开发环境。

   > 终端运行 `npm run docs-expose:dev` 可将本地的服务对外暴露。

3. 浏览器访问对应路径即可本地查看文档。

## 结构说明

```text
├── docs
│   ├── .vitepress
│   │   ├── config.mts
│   │   └── meta.mts
│   ├── guide
│   ├── index.md
│   ├── public
│   ├── solution
│   └── standard
└── package.json
```

- `package.json`: 工程配置
- `docs`: 文档目录
  
    - `.vitepress`: 文档配置目录，其中 `config.mts` 为配置文件，导航、菜单、样式、交互等都在此进行配置。`meta.mts` 为配置所依赖的元数据。
    - `public`: 静态资源。
    - `guide`: 学习指南根目录。
    - `solution`: 解决方案根目录。 
    - `standard`: 标准化根目录。
    - `index.md`: 首页。

