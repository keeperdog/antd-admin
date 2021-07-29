## Usage

1. Clone project code.

```bash
git clone https://github.com/keeperdog/antd-admin.git
cd my-project
```

2. Installation dependence.

```bash
yarn install
```

Or

```bash
npm install
```

3. Start local server.

```bash
npm run start
```

4. After the startup is complete, open a browser and visit [http://localhost:7000](http://localhost:7000), If you need to change the startup port, you can configure it in the `.env` file.

## 目录结构

├── dist/ # 默认 build 输出目录
├── mock/ # Mock 文件目录
├── public/ # 静态资源文件目录
├── src/ # 源码目录
│ ├── components/ # 组件目录
│ ├── e2e/ # e2e 目录
│ ├── layouts/ # 布局目录
│ ├── locales/ # 国际化文件目录
│ ├── models/ # 数据模型目录
│ ├── pages/ # 页面组件目录
│ ├── services/ # 数据接口目录
│ │ ├── api.js # 接口配置
│ │ └── index.js # 接口输出
│ ├── themes/ # 项目样式目录
│ │ ├── default.less # 样式变量
│ │ ├── index.less # 全局样式
│ │ ├── mixin.less # 样式函数
│ │ └── vars.less # 样式变量及函数
│ ├── utils/ # 工具函数目录
│ │ ├── config.js # 项目配置
│ │ ├── constant.js # 静态常量
│ │ ├── index.js # 工具函数
│ │ ├── request.js # 异步请求函数(axios)
│ │ └── theme.js # 项目需要在 js 中使用到样式变量
├── .editorconfig # 编辑器配置
├── .env # 环境变量
├── .eslintrc # ESlint 配置
├── .gitignore # Git 忽略文件配置
├── .prettierignore # Prettier 忽略文件配置
├── .prettierrc # Prettier 配置
├── .stylelintrc.json # Stylelint 配置
├── .travis.yml # Travis 配置
└── .umirc.js # Umi 配置
└── package.json # 项目信息
