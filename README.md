# awesome-f2e-libs

> 整理我平时关注的前端库。

## 打包工具

* [**webpack**][1] - 打包项目。
* [**rollup**][2] - 打包 npm 库。
* [**parcel**][3] - webpack 竞品，但发展前景不乐观，再观察一段时间。
* [**@pikapkg/pack**][4] - 又一组件打包工具。
* [**systemjs**][5] - 针对一些特殊场景会比较有用，比如云 ide，支付宝小程序 IDE 等。
* [**microbundle**][6] - 基于 rollup，简化配置。
* [**bili**][7] - 基于 rollup，同上。
* [**webpack-dev-server**][8] - webpack 开发服务器。
* [**webpack-dev-middleware**][9] - webpack 中间件。
* [**vue-cli**][10] - vue 命令行工具。
* [**create-react-app**][11] - react 官方脚手架。
* [**webpack-merge**][12] - 合并 webpack 配置。
* [**webpack-chain**][13] - 通过 chain 风格 api 的方式修改 webpack 配置。
* [**prepack**][14] - 通过预先执行的方式优化打包结果。
* [**swc**][15] - 基于 rust 的语法转换器，babel 的竞争者。
* [**nathan/pax**][16] - 基于 rust，据说是这个星球最快的 JavaScript 打包工具。
* [**pikapkg/web**][17] - 浏览器里跑 npm 依赖，面向现代浏览器。
* [**lebab/lebab**][18] - 把 es5 代码转成 es6，反向 babel。
* [**palmerhq/tsdx**][19] - Zero-config CLI for TypeScript package development.

### webpack loader 和插件

* [**hard-source-webpack-plugin**][20] - 性能提升 70%，但有坑。
* [**svgr**][21] - svg 转 react 组件。
* [**postcss**][22] - CSS 界的 babel。
* [**autoprefixer**][23] - 为 CSS 选择权自动加 prefix。
* [**cssnano**][24] - CSS 压缩，也有类 preset 的概念。
* [**mini-css-extract-plugin**][25] - 提取 CSS 为单独文件。
* [**webpackbar**][26] - webpack 进度条。
* [**webpack-bundle-analyzer**][27] - 构建产物占比分析。
* [**uglifyjs-webpack-plugin**][28] - JS 压缩，产物为 ES5 语法。
* [**terser-webpack-plugin**][29] - JS 压缩，产物为 ES6 语法。
* [**webpack-manifest-plugin**][30] - 生成 manifest.json。
* [**copy-webpack-plugin**][31] - 复制额外的文件到输出目录。
* [**case-sensitive-paths-webpack-plugin**][32] - 大小写敏感检测，能规避一些问题，但构建时性能消耗较大。
* [**css-hot-loader**][33] - CSS 热更新，搭配 mini-css-extract-plugin 使用。
* [**duplicate-package-checker-webpack-plugin**][34] - 重复依赖检测。
* [**fork-ts-checker-webpack-plugin**][35] - ts 语法检测。
* [**speed-measure-webpack-plugin**][36] - 统计 webpack 各阶段耗时。

## 包管理

* [**yarn**][37] - 我用这个。
* [**npm**][38]

## babel

* [**babel**][39]
* [**babel-plugin-rawest**][40] - React 的 DOM 直出方案。
* [**babel-plugin-macros**][41] - 前端文件写 node 逻辑。
* [**babel-plugin-dynamic-import-node**][42] - 有些场景下会需要禁用 `import()` 语法。
* [**babel-plugin-react-require**][43] - 自动为 jsx 语法加 react 引用。
* [**babel-plugin-transform-react-remove-prop-types**][44] - 删除 prop-types，生产环境用。

## 测试

* [**jest**][45]
* [**ts-jest**][46]
* [**enzyme**][47]
* [**jsdom**][48]
* [**puppeteer**][49]
* [**react-test-rerender**][50] - 官方出品。
* [**react-testing-library**][51] - kentcdodds 出品。

## 框架

* [**react**][52]
* [**vue**][53]
* [**next.js**][54]
* [**nuxt.js**][55]
* [**gastby**][56]
* [**umi**][57] - 蚂蚁金服的前端框架，我目前在维护。
* [**rekit**][58] - IDE and toolkit for building scalable web applications with React, Redux and React-router.
* [**choo**][59] - dva 最初的 API 是参考这个实现的，已经不怎么发展了，再关注一段时间。
* [**taro**][60] - 用 React 写小程序，适配微信和支付宝等。
* [**after.js**][61]
* [**mint**][62] - 提供了语言层方案的框架。
* [**quasar**][63] - 基于 vue，一套代码多处适用。

## react 相关库

* [**preact**][64] - 轻量级 React 实现。
* [**inferno**][65] - 轻量级 React 实现。
* [**react-router**][66] - React 路由方案。
* [**reach-router**][67] - React 路由方案，较新，优势是可访问性。
* [**router5**][68] - 通用的路由方案。
* [**react-loadable**][69] - 按需加载 react 组件。
* [**ant-design**][70] - 蚂蚁金服的 React UI 库。
* [**material-ui**][71] - UI 库。
* [**react-intl**][72] - React 的国际化方案。
* [**react-dnd**][73] - 拖拽实现。
* [**react-helmet**][74] - 修改 html 的 header 内容。
* [**react-jsonschema-form**][75] - A React component for building Web forms from JSON Schema.

## vue 相关库

* [**vue-router**][76]

## 工具类

* [**history**][77]
* [**path-to-regexp**][78] - path 转正则，路由相关处理的底层库。
* [**lodash**][79] - 工具集合。
* [**fastclick**][80]
* [**date-fns**][81] - 时间处理。

## 数据流

* [**redux**][82]
* [**immer**][83]
* [**mobx**][84]
* [**unstated**][85]
* [**rxjs**][86]
* [**dva**][87] - 我写的数据流，基于 redux。
* [**rematch**][88] - 基于 redux。
* [**vuex**][89]
* [**ngrx**][90]

### redux 扩展

* [**react-redux**][91] - 绑定 react 和 redux。
* [**redux-saga**][92]
* [**redux-persist**][93]
* [**redux-bundler**][94]
* [**redux-box**][95]

## 性能优化

* [**workbox**][96] - PWA 方案，Google 出品。
* [**critical**][97] - 提取关键 CSS。

## 语言

* [**typescript**][98]
* [**flow**][99]
* [**graphql**][100]

## 文档

* [**vuepress**][101]
* [**docz**][102]
* [**storybook**][103]
* [**mdx**][104] - jsx + markdown。

## 工程

* [**lerna**][105] - monorepo 管理。
* [**lerna-changelog**][106] - 为 lerna 项目自动生成 changelog。
* [**eslint**][107] - JS 风格约束。
* [**eslint-config-airbnb**][108]
* [**xo**][109] - 封装自 eslint。
* [**prettier**][110] - 更主观的风格自动修改。
* [**yeoman-generator**][111] - 脚手架工具。
* [**serve**][112] - 本地静态服务器。
* [**servor**][113] - 另一个静态服务器。
* [**budo**][114] - 又一个静态服务器。
* [**np**][115] - npm publish 辅助，自动 push、打 tag、升版本等。
* [**lint-staged**][116] - eslint 提速，只 lint 提交的代码。
* [**coveralls**][117] - 覆盖率。
* [**husky**][118] - 添加 git hooks。
* [**cross-env**][119] - 跨平台的环境变量声明。
* [**projj**][120] - 本地 git 项目管理，支持 github 和 gitlab。
* [**nvm**][121] - 管理 node 版本。
* [**concurrently**][122] - 在 npm scripts 里并行执行命令。
* [**@zeit/ncc**][123] - 打包为 npm 包为一个文件。
* [**npm-check**][124] - 检测依赖升级情况，我会和 `yarn upgrade-interactive` 配合着用，主要用来检测冗余依赖。
* [**cpx**][125] - 复制，支持 glob，并且可以 watch。
* [**onchange**][126] - 监听文件变动然后做一些事。
* [**just**][127] - 微软出的任务管理器。
* [**tern**][128] - 代码分析器，为不少编辑器服务。

## 编辑器

* [**VSCode**][129]
* [**IntelliJ IDEA**][130] - 我用这个。
* [**codesandbox**][131]
* [**stackblitz**][132]

## CloudIDE

* [**theia**][133]
* [**che**][134]
* [**codesandbox-client**][135]

## 字体

* [**FiraCode**][136]
* [**Dank Mono**][137]
* [**Operator Mono**][138]

## CSS

* [**css modules**][139]
* [**emotion**][140]

## 命令行

* [**yargs**][141] - 命令行入口套件。
* [**yargs-parser**][142] - 命令行参数解析。
* [**chalk**][143] - 输出不同颜色。
* [**cheerio**][144] - 用类 jQuery 语法处理 HTML。
* [**chokidar**][145] - 文件监听。
* [**clipboardy**][146] - 复制文本到粘贴板。
* [**debug**][147] - 打印调试信息。
* [**deprecate**][148] - 给过期警告。
* [**glob**][149] - 文件查找。
* [**tiny-glob**][150] - 文件查找。
* [**signale**][151] - 漂亮的日志打印。
* [**semver**][152] - semver 版本处理。
* [**update-notifier**][153] - 更新提醒。
* [**rimraf**][154] - 删除文件。
* [**depd**][155] - 给出 deprecated 警告。
* [**execa**][156] - 比 child\_process 好用，返回 Promise。
* [**ora**][157] - 控制命令行光标，显示 loading 等。
* [**inquirer**][158] - 交互式命令接口，比如 prompt。
* [**enquirer**][159] - 同上，更 cool 一些。
* [**ajv**][160] - 参数校验。
* [**ink**][161] - 用 React 处理命令行输出。
* [**figures**][162] - ✔︎ 等特殊字符，做了 windows 兼容处理。

## 请求处理

* [**whatwg-fetch**][163]
* [**got**][164]
* [**axios**][165]
* [**request**][166]
* [**reqwest**][167]

## 压缩解压缩

* [**yazl**][168] - zip 压缩。
* [**yauzl**][169] - zip 解压缩。
* [**tar-fs**][170] - tar 的压缩和解压缩。

## 语法解析

* [**esquery**][171] - 语法树查询。

## Markdown

* [**remark**][172] - Markdown 语法解析器。
* [**markdown-it**][173] - Markdown 转 HTML。

## 其他

* [**electron**][174]
* [**DeskGap**][175] - 类 electron，由于不包含浏览器的部分，所以产物更小
* [**fx**][176] - 交互式 JSON 查看。

## rtfs

- [**reactjs/rfcs**][177]
- [**eslint/rfcs**][178]
- [**vuejs/rfcs**][179]
- [**yarnpkg/rfcs**][180]
- [**npm/rfcs**][181]
- [**gastbyjs/rfcs**][182]
- [**nuxtjs/rfcs**][183]

## 相关

- [awesome-tools][184] - 我在用的工具。

[1]:	https://github.com/webpack/webpack
[2]:	https://github.com/rollup/rollup
[3]:	https://github.com/parcel-bundler/parcel
[4]:	https://github.com/pikapkg/pack
[5]:	https://github.com/systemjs/systemjs
[6]:	https://github.com/developit/microbundle
[7]:	https://github.com/egoist/bili
[8]:	https://github.com/webpack/webpack-dev-server
[9]:	https://github.com/webpack/webpack-dev-middleware
[10]:	https://github.com/vuejs/vue-cli
[11]:	https://github.com/facebook/create-react-app
[12]:	https://github.com/survivejs/webpack-merge
[13]:	https://github.com/neutrinojs/webpack-chain
[14]:	https://github.com/facebook/prepack
[15]:	https://github.com/swc-project/swc
[16]:	https://github.com/nathan/pax
[17]:	https://github.com/pikapkg/web
[18]:	https://github.com/lebab/lebab
[19]:	https://github.com/palmerhq/tsdx
[20]:	https://github.com/mzgoddard/hard-source-webpack-plugin
[21]:	https://github.com/smooth-code/svgr
[22]:	https://github.com/postcss/postcss
[23]:	https://github.com/postcss/autoprefixer
[24]:	https://github.com/cssnano/cssnano
[25]:	https://github.com/webpack-contrib/mini-css-extract-plugin
[26]:	https://github.com/nuxt/webpackbar
[27]:	https://github.com/webpack-contrib/webpack-bundle-analyzer
[28]:	https://github.com/webpack-contrib/uglifyjs-webpack-plugin
[29]:	https://github.com/webpack-contrib/terser-webpack-plugin
[30]:	https://github.com/danethurber/webpack-manifest-plugin
[31]:	https://github.com/webpack-contrib/copy-webpack-plugin
[32]:	https://github.com/Urthen/case-sensitive-paths-webpack-plugin
[33]:	https://github.com/shepherdwind/css-hot-loader
[34]:	https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin
[35]:	https://github.com/Realytics/fork-ts-checker-webpack-plugin
[36]:	https://github.com/stephencookdev/speed-measure-webpack-plugin
[37]:	https://github.com/yarnpkg/yarn
[38]:	https://github.com/npm/cli
[39]:	https://github.com/babel/babel
[40]:	https://github.com/sokra/rawact
[41]:	https://github.com/kentcdodds/babel-plugin-macros
[42]:	https://github.com/airbnb/babel-plugin-dynamic-import-node
[43]:	https://github.com/vslinko/babel-plugin-react-require
[44]:	https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types
[45]:	https://github.com/facebook/jest
[46]:	https://github.com/kulshekhar/ts-jest
[47]:	https://github.com/airbnb/enzyme
[48]:	https://github.com/jsdom/jsdom
[49]:	https://github.com/GoogleChrome/puppeteer
[50]:	https://github.com/facebook/react/tree/master/packages/react-test-renderer
[51]:	https://github.com/kentcdodds/react-testing-library
[52]:	https://github.com/facebook/react
[53]:	https://github.com/vuejs/vue
[54]:	https://github.com/zeit/next.js
[55]:	https://github.com/nuxt/nuxt.js
[56]:	https://github.com/gatsbyjs/gatsby
[57]:	https://github.com/umijs/umi
[58]:	https://github.com/rekit/rekit
[59]:	https://github.com/choojs/choo
[60]:	https://github.com/NervJS/taro
[61]:	https://github.com/jaredpalmer/after.js
[62]:	https://github.com/mint-lang/mint
[63]:	https://github.com/quasarframework/quasar
[64]:	https://github.com/developit/preact
[65]:	https://github.com/infernojs/inferno
[66]:	https://github.com/ReactTraining/react-router
[67]:	https://github.com/reach/router
[68]:	https://github.com/router5/router5
[69]:	https://github.com/jamiebuilds/react-loadable
[70]:	https://github.com/ant-design/ant-design
[71]:	https://github.com/mui-org/material-ui
[72]:	https://github.com/yahoo/react-intl
[73]:	https://github.com/react-dnd/react-dnd
[74]:	https://github.com/nfl/react-helmet
[75]:	https://github.com/mozilla-services/react-jsonschema-form
[76]:	https://github.com/vuejs/vue-router
[77]:	https://github.com/ReactTraining/history
[78]:	https://github.com/pillarjs/path-to-regexp
[79]:	https://github.com/lodash/lodash
[80]:	https://github.com/ftlabs/fastclick
[81]:	https://github.com/date-fns/date-fns
[82]:	https://github.com/reduxjs/redux
[83]:	https://github.com/mweststrate/immer
[84]:	https://github.com/mobxjs/mobx
[85]:	https://github.com/jamiebuilds/unstated
[86]:	https://github.com/ReactiveX/rxjs
[87]:	https://github.com/dvajs/dva
[88]:	https://github.com/rematch/rematch
[89]:	https://github.com/vuejs/vuex
[90]:	https://github.com/ngrx/platform
[91]:	https://github.com/reduxjs/react-redux
[92]:	https://github.com/redux-saga/redux-saga
[93]:	https://github.com/rt2zz/redux-persist
[94]:	https://github.com/henrikjoreteg/redux-bundler
[95]:	https://github.com/anish000kumar/redux-box
[96]:	https://github.com/GoogleChrome/workbox
[97]:	https://github.com/addyosmani/critical
[98]:	https://github.com/Microsoft/TypeScript
[99]:	https://github.com/facebook/flow
[100]:	https://github.com/graphql/graphql-js
[101]:	https://github.com/vuejs/vuepress
[102]:	https://github.com/pedronauck/docz
[103]:	https://github.com/storybooks/storybook
[104]:	https://github.com/mdx-js/mdx
[105]:	https://github.com/lerna/lerna
[106]:	https://github.com/lerna/lerna-changelog
[107]:	https://github.com/eslint/eslint
[108]:	https://github.com/airbnb/javascript
[109]:	https://github.com/xojs/xo
[110]:	https://github.com/prettier/prettier
[111]:	https://github.com/yeoman/generator
[112]:	https://github.com/zeit/serve
[113]:	https://github.com/lukejacksonn/servor
[114]:	https://github.com/mattdesl/budo
[115]:	https://github.com/sindresorhus/np
[116]:	https://github.com/okonet/lint-staged
[117]:	https://github.com/marketplace/coveralls
[118]:	https://github.com/typicode/husky
[119]:	https://github.com/kentcdodds/cross-env
[120]:	https://github.com/popomore/projj
[121]:	https://github.com/creationix/nvm
[122]:	https://github.com/kimmobrunfeldt/concurrently
[123]:	https://github.com/zeit/ncc
[124]:	https://github.com/dylang/npm-check
[125]:	https://github.com/mysticatea/cpx
[126]:	https://github.com/Qard/onchange
[127]:	https://github.com/Microsoft/just
[128]:	https://github.com/ternjs/tern
[129]:	https://code.visualstudio.com/
[130]:	https://www.jetbrains.com/idea/
[131]:	https://codesandbox.io/
[132]:	https://stackblitz.com/
[133]:	https://github.com/theia-ide/theia
[134]:	https://github.com/eclipse/che
[135]:	https://github.com/CompuIves/codesandbox-client
[136]:	https://github.com/tonsky/FiraCode
[137]:	https://dank.sh/
[138]:	https://www.typography.com/blog/introducing-operator
[139]:	https://github.com/css-modules/css-modules
[140]:	https://github.com/emotion-js/emotion
[141]:	https://github.com/yargs/yargs
[142]:	https://github.com/yargs/yargs-parser
[143]:	https://github.com/chalk/chalk
[144]:	https://github.com/cheeriojs/cheerio
[145]:	https://github.com/paulmillr/chokidar
[146]:	https://github.com/sindresorhus/clipboardy
[147]:	https://github.com/visionmedia/debug
[148]:	https://github.com/brianc/node-deprecate
[149]:	https://github.com/isaacs/node-glob
[150]:	https://github.com/terkelg/tiny-glob
[151]:	https://github.com/klaussinani/signale
[152]:	https://github.com/npm/node-semver
[153]:	https://github.com/yeoman/update-notifier
[154]:	https://github.com/isaacs/rimraf
[155]:	https://github.com/dougwilson/nodejs-depd
[156]:	https://github.com/sindresorhus/execa
[157]:	https://github.com/sindresorhus/ora
[158]:	https://github.com/SBoudrias/Inquirer.js
[159]:	https://github.com/enquirer/enquirer
[160]:	https://github.com/epoberezkin/ajv
[161]:	https://github.com/vadimdemedes/ink
[162]:	https://github.com/sindresorhus/figures
[163]:	https://github.com/github/fetch
[164]:	https://github.com/sindresorhus/got
[165]:	https://github.com/axios/axios
[166]:	https://github.com/request/request
[167]:	https://github.com/ded/reqwest
[168]:	https://www.npmjs.com/package/yazl
[169]:	https://github.com/thejoshwolfe/yauzl
[170]:	https://github.com/mafintosh/tar-fs
[171]:	https://github.com/estools/esquery
[172]:	https://github.com/remarkjs/remark
[173]:	https://github.com/markdown-it/markdown-it
[174]:	https://github.com/electron/electron
[175]:	https://github.com/patr0nus/DeskGap/
[176]:	https://github.com/antonmedv/fx
[177]:	https://github.com/reactjs/rfcs
[178]:	https://github.com/eslint/rfcs
[179]:	https://github.com/vuejs/rfcs
[180]:	https://github.com/yarnpkg/rfcs
[181]:	https://github.com/npm/rfcs
[182]:	https://github.com/gatsbyjs/rfcs
[183]:	https://github.com/nuxt/rfcs
[184]:	https://github.com/sorrycc/awesome-tools