# awesome-f2e-libs

> 整理我平时关注的前端库。

## 打包工具

* [**webpack**](https://github.com/webpack/webpack) - 打包项目。
* [**rollup**](https://github.com/rollup/rollup) - 打包 npm 库。
* [**parcel**](https://github.com/parcel-bundler/parcel) - webpack 竞品，但发展前景不乐观，再观察一段时间。
* [**systemjs**](https://github.com/systemjs/systemjs) - 针对一些特殊场景会比较有用，比如云 ide，支付宝小程序 IDE 等。
* [**microbundle**](https://github.com/developit/microbundle) - 基于 rollup，简化配置。
* [**bili**](https://github.com/egoist/bili) - 基于 rollup，同上。
* [**father**](https://github.com/umijs/father) - 组件打包工具，提供 babel 和 rollup 两种打包方式。
* [**vue-cli**](https://github.com/vuejs/vue-cli) - vue 命令行工具。
* [**create-react-app**](https://github.com/facebook/create-react-app) - react 官方脚手架。
* [**prepack**](https://github.com/facebook/prepack) - 通过预先执行的方式优化打包结果。
* [**lebab**](https://github.com/lebab/lebab) - 把 es5 代码转成 es6，反向 babel。
* [**esm-to-cjs**](https://github.com/sidvishnoi/esm-to-cjs) - 把 esm 转成 cjs。
* [**tsdx**](https://github.com/palmerhq/tsdx) - Zero-config CLI for TypeScript package development.

### webpack 辅助工具、Loader 和插件

* [**webpack-dev-server**](https://github.com/webpack/webpack-dev-server) - webpack 开发服务器。
* [**webpack-dev-middleware**](https://github.com/webpack/webpack-dev-middleware) - webpack 中间件。
* [**webpack-merge**](https://github.com/survivejs/webpack-merge) - 合并 webpack 配置。
* [**webpack-chain**](https://github.com/neutrinojs/webpack-chain) - 通过 chain 风格 api 的方式修改 webpack 配置。
* [**svgr**](https://github.com/smooth-code/svgr) - svg 转 react 组件。
* [**postcss**](https://github.com/postcss/postcss) - CSS 界的 babel。
* [**autoprefixer**](https://github.com/postcss/autoprefixer) - 为 CSS 选择权自动加 prefix。
* [**cssnano**](https://github.com/cssnano/cssnano) - CSS 压缩，也有类 preset 的概念。
* [**mini-css-extract-plugin**](https://github.com/webpack-contrib/mini-css-extract-plugin) - 提取 CSS 为单独文件。
* [**webpackbar**](https://github.com/nuxt/webpackbar) - webpack 进度条。
* [**webpack-bundle-analyzer**](https://github.com/webpack-contrib/webpack-bundle-analyzer) - 构建产物占比分析。
* [**uglifyjs-webpack-plugin**](https://github.com/webpack-contrib/uglifyjs-webpack-plugin) - JS 压缩，产物为 ES5 语法。
* [**terser-webpack-plugin**](https://github.com/webpack-contrib/terser-webpack-plugin) - JS 压缩，产物为 ES6 语法。
* [**webpack-manifest-plugin**](https://github.com/danethurber/webpack-manifest-plugin) - 生成 manifest.json。
* [**copy-webpack-plugin**](https://github.com/webpack-contrib/copy-webpack-plugin) - 复制额外的文件到输出目录。
* [**case-sensitive-paths-webpack-plugin**](https://github.com/Urthen/case-sensitive-paths-webpack-plugin) - 大小写敏感检测，能规避一些问题，但构建时性能消耗较大。
* [**css-hot-loader**](https://github.com/shepherdwind/css-hot-loader) - CSS 热更新，搭配 mini-css-extract-plugin 使用。
* [**duplicate-package-checker-webpack-plugin**](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - 重复依赖检测。
* [**fork-ts-checker-webpack-plugin**](https://github.com/Realytics/fork-ts-checker-webpack-plugin) - ts 语法检测。
* [**speed-measure-webpack-plugin**](https://github.com/stephencookdev/speed-measure-webpack-plugin) - 统计 webpack 各阶段耗时。

### Bundless

* [**vite**](https://github.com/vitejs/vite)
* [**snowpack**](https://github.com/pikapkg/snowpack) - 浏览器里跑 npm 依赖，面向现代浏览器。
* [**es-dev-server**](https://github.com/open-wc/open-wc/tree/master/packages/es-dev-server)

### 非 JavaScript 编译工具

* [**boa**](https://github.com/boa-dev/boa) - 基于 Rust，嵌入式 Javascript 引擎。
* [**dprint**](https://github.com/dprint/dprint) - 基于  Rust，代码格式化工具，Prettier 替代品。
* [**elsa**](https://github.com/elsaland/elsa) - 基于 Go，JavaScript 和 TypeScript 的 runtime。 
* [**es-module-lexer**](https://github.com/guybedford/es-module-lexer) - 基于 C，输出 Web Assembly，esm 模块解析。
* [**esbuild**](https://github.com/evanw/esbuild) - 基于 Go，Webpack 替代品。
* [**esbuild-node-tsc**](https://github.com/a7ul/esbuild-node-tsc) - 用 esbuild 编译 TypeScript 项目，但不支持类型检测。
* [**minify**](https://github.com/tdewolff/minify) - 基于 Go，压缩器，支持 HTML5、CSS3、JS、JSON、SVG 和 XML。
* [**RSLint**](https://github.com/RDambrosio016/RSLint) - 基于 Rust，lint 工具。
* [**sucrase**](https://github.com/alangpierce/sucrase) - 基于 Rust，Babel 替代品。
* [**swc**](https://github.com/swc-project/swc) - 基于 rust 的语法转换器，babel 的竞争者。
* [**swc-node**](https://github.com/Brooooooklyn/swc-node)
* [**markdown-wasm**](https://github.com/rsms/markdown-wasm) - 基于 wasm 的 markdown 解析工具。

## 包管理

* [**npm**](https://github.com/npm/cli)
* [**yarn**](https://github.com/yarnpkg/yarn) - 我用这个。

## babel

* [**babel**](https://github.com/babel/babel)
* [**babel-plugin-dynamic-import-node**](https://github.com/airbnb/babel-plugin-dynamic-import-node) - 有些场景下会需要禁用 `import()` 语法。
* [**babel-plugin-macros**](https://github.com/kentcdodds/babel-plugin-macros) - 前端文件写 node 逻辑。
* [**babel-plugin-rawest**](https://github.com/sokra/rawact) - React 的 DOM 直出方案。
* [**babel-plugin-react-require**](https://github.com/vslinko/babel-plugin-react-require) - 自动为 jsx 语法加 react 引用。
* [**babel-plugin-transform-react-remove-prop-types**](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) - 删除 prop-types，生产环境用。

### macros

* [**import-all.macro**](https://github.com/kentcdodds/import-all.macro)

## 测试

* [**jest**](https://github.com/facebook/jest)
* [**ts-jest**](https://github.com/kulshekhar/ts-jest)
* [**enzyme**](https://github.com/airbnb/enzyme)
* [**jsdom**](https://github.com/jsdom/jsdom)
* [**puppeteer**](https://github.com/GoogleChrome/puppeteer)
* [**react-test-rerender**](https://github.com/facebook/react/tree/master/packages/react-test-renderer) - 官方出品。
* [**react-testing-library**](https://github.com/kentcdodds/react-testing-library) - kentcdodds 出品。

## 框架

* [**react**](https://github.com/facebook/react)
* [**vue**](https://github.com/vuejs/vue)
* [**next.js**](https://github.com/zeit/next.js)
* [**nuxt.js**](https://github.com/nuxt/nuxt.js)
* [**gastby**](https://github.com/gatsbyjs/gatsby)
* [**umi**](https://github.com/umijs/umi) - 蚂蚁金服的前端框架，我目前在维护。
* [**rekit**](https://github.com/rekit/rekit) - IDE and toolkit for building scalable web applications with React, Redux and React-router.
* [**choo**](https://github.com/choojs/choo) - dva 最初的 API 是参考这个实现的，已经不怎么发展了，再关注一段时间。
* [**taro**](https://github.com/NervJS/taro) - 用 React 写小程序，适配微信和支付宝等。
* [**after.js**](https://github.com/jaredpalmer/after.js)
* [**mint**](https://github.com/mint-lang/mint) - 提供了语言层方案的框架。
* [**quasar**](https://github.com/quasarframework/quasar) - 基于 vue，一套代码多处适用。

## react 相关库

* [**preact**](https://github.com/developit/preact) - 轻量级 React 实现。
* [**inferno**](https://github.com/infernojs/inferno) - 轻量级 React 实现。
* [**react-router**](https://github.com/ReactTraining/react-router) - React 路由方案。
* [**reach-router**](https://github.com/reach/router) - React 路由方案，较新，优势是可访问性。
* [**router5**](https://github.com/router5/router5) - 通用的路由方案。
* [**react-loadable**](https://github.com/jamiebuilds/react-loadable) - 按需加载 react 组件。
* [**ant-design**](https://github.com/ant-design/ant-design) - 蚂蚁金服的 React UI 库。
* [**material-ui**](https://github.com/mui-org/material-ui) - UI 库。
* [**react-intl**](https://github.com/yahoo/react-intl) - React 的国际化方案。
* [**react-dnd**](https://github.com/react-dnd/react-dnd) - 拖拽实现。
* [**react-helmet**](https://github.com/nfl/react-helmet) - 修改 html 的 header 内容。
* [**react-jsonschema-form**](https://github.com/mozilla-services/react-jsonschema-form) - A React component for building Web forms from JSON Schema.

## vue 相关库

* [**vue-router**](https://github.com/vuejs/vue-router)

## 工具类

* [**history**](https://github.com/ReactTraining/history)
* [**path-to-regexp**](https://github.com/pillarjs/path-to-regexp) - path 转正则，路由相关处理的底层库。
* [**lodash**](https://github.com/lodash/lodash) - 工具集合。
* [**fastclick**](https://github.com/ftlabs/fastclick)
* [**date-fns**](https://github.com/date-fns/date-fns) - 时间处理。

## 数据流

* [**redux**](https://github.com/reduxjs/redux)
* [**immer**](https://github.com/mweststrate/immer)
* [**mobx**](https://github.com/mobxjs/mobx)
* [**unstated**](https://github.com/jamiebuilds/unstated)
* [**rxjs**](https://github.com/ReactiveX/rxjs)
* [**dva**](https://github.com/dvajs/dva) - 我写的数据流，基于 redux。
* [**rematch**](https://github.com/rematch/rematch) - 基于 redux。
* [**vuex**](https://github.com/vuejs/vuex)
* [**ngrx**](https://github.com/ngrx/platform)

### redux 扩展

* [**react-redux**](https://github.com/reduxjs/react-redux) - 绑定 react 和 redux。
* [**redux-saga**](https://github.com/redux-saga/redux-saga)
* [**redux-persist**](https://github.com/rt2zz/redux-persist)
* [**redux-bundler**](https://github.com/henrikjoreteg/redux-bundler)
* [**redux-box**](https://github.com/anish000kumar/redux-box)

## 性能优化

* [**workbox**](https://github.com/GoogleChrome/workbox) - PWA 方案，Google 出品。
* [**critical**](https://github.com/addyosmani/critical) - 提取关键 CSS。

## 语言

* [**typescript**](https://github.com/Microsoft/TypeScript)
* [**flow**](https://github.com/facebook/flow)
* [**graphql**](https://github.com/graphql/graphql-js)

## 文档

* [**dumi**](https://github.com/umijs/dumi)
* [**vuepress**](https://github.com/vuejs/vuepress)
* [**docz**](https://github.com/pedronauck/docz)
* [**storybook**](https://github.com/storybooks/storybook)
* [**mdx**](https://github.com/mdx-js/mdx) - jsx + markdown。

## 工程

* [**lerna**](https://github.com/lerna/lerna) - monorepo 管理。
* [**lerna-changelog**](https://github.com/lerna/lerna-changelog) - 为 lerna 项目自动生成 changelog。
* [**eslint**](https://github.com/eslint/eslint) - JS 风格约束。
* [**eslint-config-airbnb**](https://github.com/airbnb/javascript)
* [**xo**](https://github.com/xojs/xo) - 封装自 eslint。
* [**prettier**](https://github.com/prettier/prettier) - 更主观的风格自动修改。
* [**yeoman-generator**](https://github.com/yeoman/generator) - 脚手架工具。
* [**serve**](https://github.com/zeit/serve) - 本地静态服务器。
* [**servor**](https://github.com/lukejacksonn/servor) - 另一个静态服务器。
* [**budo**](https://github.com/mattdesl/budo) - 又一个静态服务器。
* [**np**](https://github.com/sindresorhus/np) - npm publish 辅助，自动 push、打 tag、升版本等。
* [**lint-staged**](https://github.com/okonet/lint-staged) - eslint 提速，只 lint 提交的代码。
* [**coveralls**](https://github.com/marketplace/coveralls) - 覆盖率。
* [**husky**](https://github.com/typicode/husky) - 添加 git hooks。
* [**cross-env**](https://github.com/kentcdodds/cross-env) - 跨平台的环境变量声明。
* [**projj**](https://github.com/popomore/projj) - 本地 git 项目管理，支持 github 和 gitlab。
* [**nvm**](https://github.com/creationix/nvm) - 管理 node 版本。
* [**concurrently**](https://github.com/kimmobrunfeldt/concurrently) - 在 npm scripts 里并行执行命令。
* [**@zeit/ncc**](https://github.com/zeit/ncc) - 打包为 npm 包为一个文件。
* [**npm-check**](https://github.com/dylang/npm-check) - 检测依赖升级情况，我会和 `yarn upgrade-interactive` 配合着用，主要用来检测冗余依赖。
* [**cpx**](https://github.com/mysticatea/cpx) - 复制，支持 glob，并且可以 watch。
* [**onchange**](https://github.com/Qard/onchange) - 监听文件变动然后做一些事。
* [**just**](https://github.com/Microsoft/just) - 微软出的任务管理器。
* [**tern**](https://github.com/ternjs/tern) - 代码分析器，为不少编辑器服务。
* [**lightproxy**](https://github.com/alibaba/lightproxy) - 底层协议代理工具，跨平台。

## 编辑器

* [**VSCode**](https://code.visualstudio.com/)
* [**IntelliJ IDEA**](https://www.jetbrains.com/idea/) - 我用这个。
* [**codesandbox**](https://codesandbox.io/)
* [**stackblitz**](https://stackblitz.com/)

## CloudIDE

* [**che**](https://github.com/eclipse/che)
* [**codesandbox-client**](https://github.com/CompuIves/codesandbox-client)
* [**theia**](https://github.com/theia-ide/theia)

## 字体

* [**Dank Mono**](https://dank.sh/)
* [**FiraCode**](https://github.com/tonsky/FiraCode)
* [**Operator Mono**](https://www.typography.com/blog/introducing-operator)

## CSS

* [**css modules**](https://github.com/css-modules/css-modules)
* [**emotion**](https://github.com/emotion-js/emotion)

## 命令行

* [**ajv**](https://github.com/epoberezkin/ajv) - 参数校验。
* [**chalk**](https://github.com/chalk/chalk) - 输出不同颜色。
* [**cheerio**](https://github.com/cheeriojs/cheerio) - 用类 jQuery 语法处理 HTML。
* [**chokidar**](https://github.com/paulmillr/chokidar) - 文件监听。
* [**clipboardy**](https://github.com/sindresorhus/clipboardy) - 复制文本到粘贴板。
* [**debug**](https://github.com/visionmedia/debug) - 打印调试信息。
* [**depd**](https://github.com/dougwilson/nodejs-depd) - 给出 deprecated 警告。
* [**deprecate**](https://github.com/brianc/node-deprecate) - 给过期警告。
* [**enquirer**](https://github.com/enquirer/enquirer) - 同上，更 cool 一些。
* [**execa**](https://github.com/sindresorhus/execa) - 比 child_process 好用，返回 Promise。
* [**figures**](https://github.com/sindresorhus/figures) - ✔︎ 等特殊字符，做了 windows 兼容处理。
* [**glob**](https://github.com/isaacs/node-glob) - 文件查找。
* [**ink**](https://github.com/vadimdemedes/ink) - 用 React 处理命令行输出。
* [**inquirer**](https://github.com/SBoudrias/Inquirer.js) - 交互式命令接口，比如 prompt。
* [**ora**](https://github.com/sindresorhus/ora) - 控制命令行光标，显示 loading 等。
* [**rimraf**](https://github.com/isaacs/rimraf) - 删除文件。
* [**signale**](https://github.com/klaussinani/signale) - 漂亮的日志打印。
* [**semver**](https://github.com/npm/node-semver) - semver 版本处理。
* [**tiny-glob**](https://github.com/terkelg/tiny-glob) - 文件查找。
* [**update-notifier**](https://github.com/yeoman/update-notifier) - 更新提醒。
* [**yargs**](https://github.com/yargs/yargs) - 命令行入口套件。
* [**yargs-parser**](https://github.com/yargs/yargs-parser) - 命令行参数解析。

## 请求处理

* [**axios**](https://github.com/axios/axios)
* [**got**](https://github.com/sindresorhus/got)
* [**request**](https://github.com/request/request)
* [**reqwest**](https://github.com/ded/reqwest)
* [**urllib**](https://github.com/node-modules/urllib)
* [**whatwg-fetch**](https://github.com/github/fetch)

## 压缩解压缩

* [**compressing**](https://github.com/node-modules/compressing) - 压缩和解压缩。
* [**tar-fs**](https://github.com/mafintosh/tar-fs) - tar 的压缩和解压缩。
* [**yauzl**](https://github.com/thejoshwolfe/yauzl) - zip 解压缩。
* [**yazl**](https://www.npmjs.com/package/yazl) - zip 压缩。

## 语法解析

* [**esquery**](https://github.com/estools/esquery) - 语法树查询。

## Markdown

* [**markdown-it**](https://github.com/markdown-it/markdown-it) - Markdown 转 HTML。
* [**remark**](https://github.com/remarkjs/remark) - Markdown 语法解析器。

## 其他

* [**electron**](https://github.com/electron/electron)
* [**fx**](https://github.com/antonmedv/fx) - 交互式 JSON 查看。
* [**DeskGap**](https://github.com/patr0nus/DeskGap/) - 类 electron，由于不包含浏览器的部分，所以产物更小

## rtfs

* [**eslint/rfcs**](https://github.com/eslint/rfcs)
* [**gastbyjs/rfcs**](https://github.com/gatsbyjs/rfcs)
* [**npm/rfcs**](https://github.com/npm/rfcs)
* [**nuxtjs/rfcs**](https://github.com/nuxt/rfcs)
* [**reactjs/rfcs**](https://github.com/reactjs/rfcs)
* [**vuejs/rfcs**](https://github.com/vuejs/rfcs)
* [**yarnpkg/rfcs**](https://github.com/yarnpkg/rfcs)

## 相关

* [awesome-tools](https://github.com/sorrycc/awesome-tools) - 我在用的工具。
