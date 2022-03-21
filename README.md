<!-- markdownlint-disable-next-line -->
<p align="center">
  <!-- <a href="https://yarn-tsdx.js.org" rel="noopener" target="_blank"> -->
    <img height="100" src="https://github.com/yarnpkg/assets/blob/master/yarn-kitten-full.png?raw=true" alt='Logo'>
  <!-- </a> -->
</p>

<h1 align="center">
    <code>yarn-tsdx</code>
</h1>

<div align="center">

this is a [Yarn workspace](https://yarnpkg.com/features/workspaces) project composed of [multiple packages](#packages) for individual [TSDX](https://tsdx.io/) projects for quick and easy [TypeScript](https://www.typescriptlang.org/) development

![Travis](https://img.shields.io/travis/json2d/yarn-tsdx.svg)
![Coveralls github](https://img.shields.io/coveralls/github/json2d/yarn-tsdx.svg)

</div>

## getting started

to install project dependencies:

```sh
yarn install
```

to build all the packages:

```
yarn workspaces run build
```

to build a package individually:

```
cd packages/*
yarn build
```

> don't forget the build step because the builds are the targets when importing between sibling packages, not the source code itself!

## packages

- [`thing`](https://github.com/json2d/yarn-tsdx/blob/main/packages/thing)
- [`thingy`](https://github.com/json2d/yarn-tsdx/blob/main/packages/redux)