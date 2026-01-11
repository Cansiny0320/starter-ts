# pkg-placeholder

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![bundle][bundle-src]][bundle-href]
[![JSDocs][jsdocs-src]][jsdocs-href]
[![License][license-src]][license-href]

_description_

> 注意：要使用此模板，请全局替换 `pkg-placeholder`、`_description_`。

## 如何使用

1. 在 GitHub 上点击 **Use this template**（或用 `degit`/clone 本仓库）。
2. 全局替换 `pkg-placeholder` 和 `_description_`。
3. 更新归属信息：`.github/FUNDING.yml`、`README.md` 的 Sponsors/Badges、以及 `package.json` 的 `author` / `funding`。
4. 安装依赖：`pnpm i`（或使用 `@antfu/ni` 的 `nci`）。
5. 运行校验：`pnpm test` 和 `pnpm lint`。

<details>
<summary>给 AI Agents（默认折叠隐藏）</summary>

- 目标：把这个仓库改造成一个新的 TypeScript 库项目。
- 必改项：
  - 替换 `pkg-placeholder`（包名 + badges 链接）和 `_description_`。
  - 将 `Cansiny0320` 替换为目标 GitHub user/org（`README` sponsors/badges、`.github/FUNDING.yml`、`package.json` author/funding URL 等）。
- 不要做：不要全局替换依赖名（例如 `@antfu/*`）。
- 修改后运行：`pnpm i`、`pnpm lint`、`pnpm typecheck`、`pnpm test`、`pnpm build`。
- 发布注意：推送 `v*` tag 可能触发发布；在打 tag 之前先配置好 npm Trusted Publisher / 权限。

</details>

## 给开发者的说明

本模板建议使用 [npm Trusted Publisher](https://github.com/e18e/ecosystem-issues/issues/201)，把发布放到 CI 执行，以提升供应链安全。

- 首次发布：先手动执行一次 `pnpm publish` 创建 npm 包，然后访问 `https://www.npmjs.com/package/<your-package-name>/access` 绑定到你的 GitHub 仓库。
- 后续发布：运行 `pnpm run release`。

### 发布安全

- `Release` 工作流会在推送 `v*` tag 时运行，并可能尝试发布。
- 推 tag 前请先配置好 npm Trusted Publisher（或所需 secrets/权限）。

### 关于 pnpm catalog

此模板使用 pnpm 的 `catalog:` 版本（见 `pnpm-workspace.yaml`）。如果你不想用它，把 `package.json` 里的 `catalog:*` 换成明确的 semver 版本即可。

## Sponsors

如果你觉得这个项目有帮助，可以考虑通过 GitHub Sponsors 支持：

https://github.com/sponsors/Cansiny0320

## License

[MIT](./LICENSE.md) License © [Cansiny0320](https://github.com/Cansiny0320)

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/pkg-placeholder?style=flat&colorA=080f12&colorB=1fa669
[npm-version-href]: https://npmjs.com/package/pkg-placeholder
[npm-downloads-src]: https://img.shields.io/npm/dm/pkg-placeholder?style=flat&colorA=080f12&colorB=1fa669
[npm-downloads-href]: https://npmjs.com/package/pkg-placeholder
[bundle-src]: https://img.shields.io/bundlephobia/minzip/pkg-placeholder?style=flat&colorA=080f12&colorB=1fa669&label=minzip
[bundle-href]: https://bundlephobia.com/result?p=pkg-placeholder
[license-src]: https://img.shields.io/github/license/Cansiny0320/pkg-placeholder.svg?style=flat&colorA=080f12&colorB=1fa669
[license-href]: https://github.com/Cansiny0320/pkg-placeholder/blob/master/LICENSE.md
[jsdocs-src]: https://img.shields.io/badge/jsdocs-reference-080f12?style=flat&colorA=080f12&colorB=1fa669
[jsdocs-href]: https://www.jsdocs.io/package/pkg-placeholder
