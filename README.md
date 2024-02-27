# `@joaopalmeiro/prettier-vue-config`

My personal Prettier config for Vue/Nuxt projects.


- [Source code](https://github.com/joaopalmeiro/prettier-vue-config)
- [npm package](https://www.npmjs.com/package/@joaopalmeiro/prettier-vue-config)
- [Licenses](https://licenses.dev/npm/%40joaopalmeiro%2Fprettier-vue-config/0.0.0)

## Getting Started

### Installation

```bash
npm install --save-dev @joaopalmeiro/prettier-vue-config
```

or

```bash
yarn add --dev @joaopalmeiro/prettier-vue-config
```

or

```bash
pnpm add --save-dev @joaopalmeiro/prettier-vue-config
```

or

```bash
bun add --dev @joaopalmeiro/prettier-vue-config
```

### Usage

To use this configuration, choose one of the options below.

#### Edit the `package.json` file

```json
{
  "prettier": "@joaopalmeiro/prettier-vue-config"
}
```

#### Create a `.prettierrc` file

```json
"@joaopalmeiro/prettier-vue-config"
```

Check the [Configuration Overrides](https://prettier.io/docs/en/configuration.html#configuration-overrides) and [Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations) sections in the Prettier documentation to learn how to override this configuration.

## References

Check out the [Awesome Prettier](https://gitlab.com/joaommpalmeiro/awesome-prettier) repo.

## Development

Install [fnm](https://github.com/Schniz/fnm) (if necessary).

```bash
fnm install && fnm use && node --version && npm --version
```

```bash
npm install
```

```bash
npm run lint
```

```bash
npm run format
```

## Deployment

```bash
npm pack --dry-run
```

```bash
npm version patch
```

```bash
npm version minor
```

```bash
npm version major
```

- Update the version in the `Licenses` link at the top.
- Commit and push changes.
- Create a tag on [GitHub Desktop](https://github.blog/2020-05-12-create-and-push-tags-in-the-latest-github-desktop-2-5-release/).
- Check [GitHub](https://github.com/joaopalmeiro/prettier-vue-config/tags).

```bash
npm login
```

```bash
npm publish
```

- Check [npm](https://www.npmjs.com/package/@joaopalmeiro/prettier-vue-config).
