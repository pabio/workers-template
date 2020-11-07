# ☁️ Workers Template

This is a starter repository for building Cloudflare Workers projects using Node.js and TypeScript at Koj.

<!-- prettier-ignore-start -->
|   | Status |
| - | - |
| Build | [![Node CI](https://github.com/koj-co/workers-template/workflows/Node%20CI/badge.svg)](https://github.com/koj-co/workers-template/actions?query=workflow%3A%22Node+CI%22) [![Dependencies](https://img.shields.io/librariesio/github/koj-co/workers-template)](https://libraries.io/github/koj-co/workers-template) [![GitHub release (latest by date)](https://img.shields.io/github/v/release/koj-co/workers-template)](https://github.com/koj-co/workers-template/releases) [![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/koj-co/workers-template)](https://snyk.io/test/github/koj-co/workers-template) |
| Health | [![CLA Assistant](https://github.com/koj-co/workers-template/workflows/CLA%20Assistant/badge.svg)](https://github.com/koj-co/workers-template/actions?query=workflow%3A%22CLA+Assistant%22) [![Pull Request Labeler](https://github.com/koj-co/workers-template/workflows/Pull%20Request%20Labeler/badge.svg)](https://github.com/koj-co/workers-template/actions?query=workflow%3A%22Pull+Request+Labeler%22) |
| PRs | [![PR Generator CI](https://github.com/koj-co/workers-template/workflows/PR%20Generator%20CI/badge.svg)](https://github.com/koj-co/workers-template/actions?query=workflow%3A%22PR+Generator+CI%22) [![Merge PRs](https://github.com/koj-co/workers-template/workflows/Merge%20PRs/badge.svg)](https://github.com/koj-co/workers-template/actions?query=workflow%3A%22Merge+PRs%22) |
<!-- prettier-ignore-end -->

## ⭐️ Features

- [Semantic Release with Gitmoji](./release.config.js)
- [Koj's Prettier configuration](./.prettierrc.cjs)
- [Dependabot configuration](./.github/dependabot.yml)
- [CI for open-source licenses](./.github/workflows/licensed.yml)
- [Pull request labeler](./.github/labeler.yml)
- [Merge PRs on approved reviews](./github/workflows/automerge.yml)
- [CLA enforcement for new contributors](./github/workflows/cla.yml)
- [Create PRs from feature/hotfix branches](./github/workflows/feature-pr.yml)
- [Write code in TypeScript](./src/index.ts)
- [Tests using Jest](./src/index.spec.ts)
- [Based on Cloudflare's Workers template](https://github.com/cloudflare/worker-typescript-template)

## 💻 Getting started

1. [Create a new repository from this template](https://github.com/koj-co/workers-template/generate)
2. Install dependencies using `npm install`
3. Update package details in `package.json` and `README.md`
   1. Find and replace `koj-co/workers-template` with `user/repository`
   2. Find and replace `@koj/workers-template` with npm project name

## 📄 License

[MIT](./LICENSE) © [Koj](https://koj.co)

<p align="center">
  <a href="https://koj.co">
    <img width="44" alt="Koj" src="https://kojcdn.com/v1598284251/website-v2/koj-github-footer_m089ze.svg">
  </a>
</p>
<p align="center">
  <sub>An open source project by <a href="https://koj.co">Koj</a>. <br> <a href="https://koj.co">Furnish your home in style, for as low as CHF175/month →</a></sub>
</p>
