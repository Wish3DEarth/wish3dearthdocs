# 与其他工具比较 {#comparisons}

## WMR {#wmr}

Preact 团队的 [WMR](https://github.com/preactjs/wmr) 提供了类似的特性集，而 Vite 2.0 对 Rollup 插件接口的支持正是受到了它的启发。

WMR 主要是为了 [Preact](https://preactjs.com/) 项目而设计，并为其提供了集成度更高的功能，比如预渲染。就使用范围而言，它更加贴合于 Preact 框架，与 Preact 本身一样强调紧凑的大小。如果你正在使用 Preact，那么 WMR 可能会提供更好的体验。

## @web/dev-server {#webdev-server}

[@web/dev-server](https://modern-web.dev/docs/dev-server/overview/)（曾经是 `es-dev-server`）是一个伟大的项目，基于 koa 的 Vite 1.0 开发服务器就是受到了它的启发。

`@web/dev-server` 适用范围不是很广。它并未提供官方的框架集成，并且需要为生产构建手动设置 Rollup 配置。

总的来说，与 `@web/dev-server` 相比，Vite 是一个更有主见、集成度更高的工具，旨在提供开箱即用的工作流。话虽如此，但 `@web` 这个项目群包含了许多其他的优秀工具，也可以使 Vite 用户受益。

## Snowpack {#snowpack}

[Snowpack](https://www.snowpack.dev/) 也是一个与 Vite 十分类似的非构建式原生 ESM 开发服务器。该项目已经不维护了。团队目前正在开发 [Astro](https://astro.build/)，一个由 Vite 驱动的静态站点构建工具。Astro 团队目前是我们生态中非常活跃的成员，它们帮助 Vite 进益良多。

除了不同的实现细节外，这两个项目在技术上比传统工具有很多共同优势。Vite 的依赖预构建也受到了 Snowpack v1（现在是 [`esinstall`](https://github.com/snowpackjs/snowpack/tree/main/esinstall)）的启发。若想了解 Vite 同这两个项目之间的一些主要区别，可以查看 [the v2 Comparisons Guide](https://v2.vitejs.dev/guide/comparisons)。
