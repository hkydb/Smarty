<br>

<p align="center">
<img src="https://github.com/hkydb/components-library/master/assets/logo.jpeg" style="width:200px;" />
</p>

<h1 align="center">Smarty</h1>

<p align="center">Web3 Components Library
</p>

<p align="center">
    <a href="https://www.npmjs.com/package/smarty-admin-ui"><img src="https://img.shields.io/npm/v/smarty-admin-ui?color=c95f8b&amp;label=" alt="NPM version"></a>
    <a href="https://github.com/smarty-team/smarty-admin/actions/workflows/main.yml"><img src="https://github.com/smarty-team/smarty-admin/actions/workflows/main.yml/badge.svg?branch=main" alt="CI" style="max-width: 100%;"></a>
</p>

Smarty is a Web3 cross platform high-performance graphics system, which can render graphics on web, node, desktop applications and mini-programs.

Smarty<sup>Next</sup> is the new version of Smarty. It is renderer agnostic enabling the same api to render in multiple contexts: webgl2, webgl, and canvas2d.

Manipulate canvas as you do with the DOM elements.



## Features
- Manipulate the sprites element as you do with the DOM elements.
- Rendering by **WebGL2** context.
- Multiple layers.
- DOM Events.
- Object Oriented Programmed Development with ES6+.
- OffscreenCanvas and [Web Worker](https://Smarty.com/#/en/guide/worker).
- Work with [d3](https://github.com/d3/d3).
- [Server-side rendering](https://Smarty.com/#/en/guide/platforms).
- Monorepo 风格 (pnpm workspace)
- 独立组件库
- 独立脚手架工具
- SSG 风格文档自动化工具
- seed 项目模板

# Archetechure

- [ UI 组件库(演示 Vite 的搭建过程) ](packages/smarty-ui-vite)
- [ UI 组件库(演示 Rollup 的搭建过程) ](packages/smarty-ui-rollup)
- [ CLI 工具(演示 CLI 工具开发过程) ](packages/create-smarty-app)
- [ 组件库文档网站(VitePress 的文档化应用) ](packages/docs-rollup/)
- [ Admin 管理(Vite Base、演示黑魔法) ](packages/admin)
- [ Admin 管理(Webpack Base 、 演示性能优化) ](packages/admin-webpack)


## What's inside?

| **Project**                                                                         | **Description**                       |
| ----------------------------------------------------------------------------------- | ------------------------------------- |
| [ReactJS](https://reactjs.org)                                                      | Rendering Smarty elements with React. |
| [Vite](https://vitejs.dev)                                                          | Next generation frontend tooling.     |
| [TypeScript](https://www.typescriptlang.org)                                        |
| [Jest](https://jestjs.io)                                                           | Testing Library.                      |
| [Cypress](https://www.cypress.io)                                                   | End-to-end testing.                   |
| [ESLint](https://eslint.org)                                                        | Linting utility.                      |
| [Prettier](https://prettier.io)                                                     | Code formatter.                       |
| [Polyfills](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy#readme) | Legacy browser support.               |

## Getting started

1. Create the project.

   ```bash
   npx degit fabien-ml/react-ts-vite-template my-app
   ```

2. Access the project directory.

   ```bash
   cd my-app
   ```

3. Initialize a git repository.

   ```bash
   git init
   ```

4. Install dependencies.

   ```bash
   npm install
   ```

5. Start dev server with hot reload at http://localhost:3000.
   ```bash
   npm run dev
   ```

## Other commands

### Lint commands

```bash
npm run lint
```

### Build commands

```bash
npm run build
```

### Run the app in production mode at http://localhost:3000.

```bash
npm run serve
```

### Test commands

- Run unit tests and watch
  ```bash
  npm run test:unit
  ```
- Run unit tests with coverage
  ```bash
  npm run test:unit:coverage
  ```
- Run e2e tests
  ```bash
  npm run test:e2e
  ```




# Compatibility

Compatible for most modern browsers.

You should import [babel-polyfill](https://cdn.baomitu.com/babel-polyfill) for early browers(i.e. iOS 8).

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->

|                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                               |                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                       |                                                                                                                                                                                                                                                                                  |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars2.githubusercontent.com/u/12529206?s=460&v=4" width="60px;"/><br /><sub><b>betseyliu</b></sub>](https://github.com/betseyliu)<br />[💻](https://github.com/Smarty/Smarty/commits?author=betseyliu "Code") [📖](https://github.com/Smarty/Smarty/commits?author=betseyliu "Documentation") |                                                                                  [<img src="https://avatars0.githubusercontent.com/u/11631503?s=460&v=4" width="60px;"/><br /><sub><b>Shero0311</b></sub>](https://github.com/Shero0311)<br />[📖](https://github.com/Smarty/Smarty/commits?author=Shero0311 "Documentation")                                                                                  | [<img src="https://avatars3.githubusercontent.com/u/16967069?s=460&v=4" width="60px;"/><br /><sub><b>有马</b></sub>](https://github.com/makeco)<br />[📖](https://github.com/Smarty/Smarty/commits?author=makeco "Documentation") [💻](https://github.com/Smarty/Smarty/commit/e2ef39bafd81ee09494f5ebbaf0f8319dbd85122 "Code") | [<img src="https://avatars1.githubusercontent.com/u/8180186?s=400&v=4" width="60px;"/><br /><sub><b>文蔺</b></sub>](https://github.com/AngusFu)<br />[💻](https://github.com/Smarty/Smarty/commits?author=AngusFu "Code") [🐛](https://github.com/Smarty/Smarty/issues/30 "Bug reports") | [<img src="https://avatars3.githubusercontent.com/u/5996758?s=400&v=4" width="60px;"/><br /><sub><b>蔡斯杰</b></sub>](https://github.com/SijieCai)<br />[💻](https://github.com/Smarty/sprite-core/commits?author=SijieCai "Code") [📖](https://github.com/Smarty/Smarty/commits?author=SijieCai "Documentation") | [<img src="https://avatars2.githubusercontent.com/u/726566?s=400&v=4" width="60px;"/><br /><sub><b>Shaofei Cheng</b></sub>](https://github.com/wintercn)<br />[💻](https://github.com/Smarty/sprite-core/commits?author=wintercn "Code") [📖](https://github.com/Smarty/Smarty/commits?author=wintercn "Documentation") |                    [<img src="https://avatars2.githubusercontent.com/u/2947893?s=400&v=4" width="60px;"/><br /><sub><b>摇太阳</b></sub>](https://github.com/yaotaiyang)<br />[📖](https://github.com/Smarty/Smarty/commits?author=yaotaiyang "Documentation")                     |
|                                         [<img src="https://avatars2.githubusercontent.com/u/424491?s=400&v=4" width="60px;"/><br /><sub><b>公子</b></sub>](https://github.com/lizheming)<br />[💻](https://github.com/Smarty/sprite-core/commits?author=lizheming "Code")                                          | [<img src="https://avatars1.githubusercontent.com/u/26452939?s=400&v=4" width="60px;"/><br /><sub><b>justemit</b></sub>](https://github.com/justemit)<br />[💻](https://github.com/Smarty/sprite-extend-shapes/commits?author=justemit "Code")  [📖](https://github.com/Smarty/sprite-extend-shapes/commits?author=justemit "Documentation") [🐛](https://github.com/Smarty/sprite-core/issues/34 "Bug reports") |                                                      [<img src="https://avatars2.githubusercontent.com/u/40935?s=400&v=4" width="60px;"/><br /><sub><b>Welefen Lee</b></sub>](https://github.com/welefen)<br />[💻](https://github.com/Smarty/sprite-flex-layout "Code")                                                       |                            [<img src="https://avatars2.githubusercontent.com/u/30425185?s=400&v=4" width="60px;"/><br /><sub><b>YUPENG12138</b></sub>](https://github.com/YUPENG12138)<br />[📖](https://github.com/Smarty/Smarty/issues/52 "Documentation")                            |                                                [<img src="https://avatars1.githubusercontent.com/u/1617414?s=400&v=4" width="60px;"/><br /><sub><b>xinde</b></sub>](https://github.com/xinde)<br />[🐛](https://github.com/Smarty/Smarty/issues/59 "Bug reports")                                                |                                               [<img src="https://avatars2.githubusercontent.com/u/13284749?s=400&v=4" width="60px;"/><br /><sub><b>ggvswild</b></sub>](https://github.com/ggvswild)<br />[🐛](https://github.com/Smarty/Smarty/issues/70 "Bug reports")                                                | [<img src="https://avatars2.githubusercontent.com/u/41336612?s=400&u=aef0eee102ca66f28c7cbd8769fa21be9dfe3697&v=4" width="60px;"/><br /><sub><b>liulinboyi</b></sub>](https://github.com/liulinboyi)<br />[💻](https://github.com/Smarty/Smarty/commits?author=liulinboyi "Code") |
|                      [<img src="https://avatars3.githubusercontent.com/u/22330483?s=400&u=93fe7b2234377c1f55feb81811354ed5af80e0c5&v=4" width="60px;"/><br /><sub><b>Lulzx</b></sub>](https://github.com/Lulzx)<br />[💻](https://github.com/Smarty/sprite-core/commits?author=Lulzx "Code")                       |                                                              [<img src="https://avatars3.githubusercontent.com/u/63718466?s=400&u=4836efce7fc68af52a4449e95e920da9ad1df34f&v=4" width="60px;"/><br /><sub><b>asidar</b></sub>](https://github.com/asidar)<br />[💻](https://github.com/Smarty/sprite-extend-shapes/commits?author=asidar "Code")                                                               |                     [<img src="https://avatars2.githubusercontent.com/u/1798972?s=400&u=36d324fd75d4f4fb14992dff084e4c013c8dc214&v=4" width="60px;"/><br /><sub><b>alphatr</b></sub>](https://github.com/alphatr)<br />[💻](https://github.com/Smarty/sprite-extend-shapes/commits?author=alphatr "Code")                      |     [<img src="https://avatars2.githubusercontent.com/u/30466018?s=400&u=e35b17b9772b1ed63f3b0c5897f3076e94a426ed&v=4" width="60px;"/><br /><sub><b>W-Qing</b></sub>](https://github.com/W-Qing)<br />[📖](https://github.com/Smarty/Smarty/commits?author=W-Qing "Documentation")      |

## License

[MIT](LICENSE)



