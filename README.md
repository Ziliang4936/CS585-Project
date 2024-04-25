

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/gekichumai/dxrating/release.yml)
![GitHub deployments](<https://img.shields.io/github/deployments/gekichumai/dxrating/dxrating%20(Production)?label=deployment>)
![GitHub License](https://img.shields.io/github/license/gekichumai/dxrating)
![GitHub Repo stars](https://img.shields.io/github/stars/gekichumai/dxrating?style=flat)
![GitHub contributors](https://img.shields.io/github/contributors/gekichumai/dxrating)

# CS 585 Project - Video Game Source Recognizer



## Apps and Packages

### Apps

- `apps/web`: the main web app that provides both the web and iOS app variant of the website

### Packages

- `packages/dxdata`: a package that provides annotated, ready to use maimai DX songs & sheets metadata, generated by `scripts/annotator`
- `packages/self-hosted-functions`: a package that provides self hosted functions wrapped with Koa.js

### Scripts

- `scripts/annotator`: a script that annotates maimai DX songs & sheets metadata from various sources

### Source-related Tools

- `packages/eslint-config-custom`: a package that provides custom ESLint configuration
- `packages/tsconfig`: a package that provides custom TypeScript configuration

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Prettier](https://prettier.io) for code formatting

### Build

To build all apps and packages, run the following command:

```bash
cd dxrating
yarn build
```

### Develop

To develop all apps and packages, run the following command:

```bash
cd dxrating
yarn dev
```

## Useful Links

Learn more about Turborepo, the monorepo tool used in this project: [Documentation](https://turbo.build/repo/docs) / [CLI Usage](https://turbo.build/docs/reference/command-line-reference)

## License

[MIT](LICENSE)

## Security

If you find a vulnerability in the repository, please email the organization owner (`vulnerability@dxrating.net`). We kindly ask you not to disclose the detail of the vulnerability to the public before we have released a fix. Thanks for making DXRating a better site!

## Contributors

This project is made possible by the following contributors. Contributions are always welcome!

[![Contributors](https://contrib.rocks/image?repo=gekichumai/dxrating)](https://github.com/gekichumai/dxrating/graphs/contributors)
