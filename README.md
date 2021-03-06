# Flow Runtime
[![Build Status](https://travis-ci.org/codemix/flow-runtime.svg?branch=master)](https://travis-ci.org/codemix/flow-runtime)

A runtime type system for JavaScript with full [Flow](https://flowtype.org/) compatibility.

[See the website for more information](https://codemix.github.io/flow-runtime/).

---

This is a [lerna](https://github.com/lerna/lerna) powered mono-repo, composed of the following projects:

  - [flow-runtime](./packages/flow-runtime): The core runtime type system.
  - [babel-plugin-flow-runtime](./packages/babel-plugin-flow-runtime): A babel plugin which transforms Flow type annotations into `flow-runtime` invocations.
  - [flow-runtime-validators](./packages/flow-runtime-validators): A collection of common validators for use with flow-runtime.
  - [flow-config-parser](./packages/flow-config-parser): Parses flow configuration files.
  - [flow-runtime-mobx](./packages/flow-runtime-mobx): Adds mobx support to flow-runtime.
  - [flow-runtime-docs](./packages/flow-runtime-docs): React powered documentation site.

## Contributing

First clone the repo:

```sh
git clone https://github.com/codemix/flow-runtime.git
```

And bootstrap the project:

```sh
cd flow-runtime
yarn
yarn bootstrap
yarn test
```
