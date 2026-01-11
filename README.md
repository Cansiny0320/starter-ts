# pkg-placeholder

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![bundle][bundle-src]][bundle-href]
[![JSDocs][jsdocs-src]][jsdocs-href]
[![License][license-src]][license-href]

_description_

> 中文版：[`README.zh-CN.md`](./README.zh-CN.md)

> Note: Replace pkg-placeholder, _description_ globally to use this template.

## How to use

1. Click **Use this template** on GitHub (or `degit`/clone this repo).
2. Globally replace `pkg-placeholder` and `_description_`.
3. Update project owner references: `.github/FUNDING.yml`, `README.md` sponsors/badges, and `package.json` `author` / `funding`.
4. Install deps: `pnpm i` (or `nci` if you use `@antfu/ni`).
5. Run checks: `pnpm test` and `pnpm lint`.

<details>
<summary>For AI agents (hidden by default)</summary>

- Goal: turn this repo into a new TS library package.
- Required edits:
  - Replace `pkg-placeholder` (package name + badges links) and `_description_`.
  - Replace `Cansiny0320` occurrences with the target GitHub user/org (README sponsors/badges, `.github/FUNDING.yml`, `package.json` author/funding URLs).
- Do NOT globally replace dependency names like `@antfu/*`.
- After edits, run: `pnpm i`, `pnpm lint`, `pnpm typecheck`, `pnpm test`, `pnpm build`.
- Release flow: pushing a `v*` tag can trigger publishing; ensure npm Trusted Publisher / tokens are configured before releasing.

</details>

## Note for Developers

This starter recommends using [npm Trusted Publisher](https://github.com/e18e/ecosystem-issues/issues/201), where the release is done on CI to improve supply-chain security.

- First-time publish: run `pnpm publish` once to create the package on npm, then visit `https://www.npmjs.com/package/<your-package-name>/access` to connect it to your GitHub repo.
- Future releases: run `pnpm run release`.

### Release safety

- The `Release` workflow runs on `v*` tags and may attempt to publish.
- Configure npm Trusted Publisher (or required secrets/permissions) before pushing tags.

### About pnpm catalog

This template uses pnpm `catalog:` versions (see `pnpm-workspace.yaml`). If you don't want that, replace `catalog:*` entries in `package.json` with explicit semver versions.

## Sponsors

If you find this project helpful, consider supporting it via GitHub Sponsors:

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
