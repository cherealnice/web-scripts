# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [5.0.1](https://github.com/spotify/web-scripts/compare/v5.0.0...v5.0.1) (2020-01-07)

### Bug Fixes

- **create-web-scripts-library:** bump template submodule ([e4280f4](https://github.com/spotify/web-scripts/commit/e4280f42dcf41ce46c5cd34ff4bde66e1d7e9bca))

# [5.0.0](https://github.com/spotify/web-scripts/compare/v4.0.2...v5.0.0) (2020-01-06)

### Features

- **tsconfig:** expose a single tsconfig ([5048d6a](https://github.com/spotify/web-scripts/commit/5048d6aea1e8949c11bfa8ed5bbdff3f177074b7)), closes [#21](https://github.com/spotify/web-scripts/issues/21)
- **web-scripts:** enable declarationMaps on types by default ([835793e](https://github.com/spotify/web-scripts/commit/835793e1038d10cba10b2c33c2a063a263f60a26)), closes [#17](https://github.com/spotify/web-scripts/issues/17)

### BREAKING CHANGES

- **tsconfig:** deleted a number of exports from tsconfig

## [4.0.2](https://github.com/spotify/web-scripts/compare/v4.0.1...v4.0.2) (2020-01-03)

### Bug Fixes

- fix commander usage of args for positional args ([1a1eb5a](https://github.com/spotify/web-scripts/commit/1a1eb5a2e7678e0201e7093da9fa0236d4fb7104))

## [4.0.1](https://github.com/spotify/web-scripts/compare/v4.0.0...v4.0.1) (2020-01-03)

### Bug Fixes

- use commander v4; re-enable lib checks in TS ([e41d9de](https://github.com/spotify/web-scripts/commit/e41d9deb3d44d3afd23d40770ac1951e9f7062f3)), closes [#95](https://github.com/spotify/web-scripts/issues/95)

# [4.0.0](https://github.com/spotify/web-scripts/compare/v3.3.1...v4.0.0) (2020-01-03)

### chore

- bump engine to >=10.13.0 ([9527453](https://github.com/spotify/web-scripts/commit/9527453a03ea0a807e6f6964469bf8482a3e3cca))

### Features

- eslint 6 updates ([d5444b6](https://github.com/spotify/web-scripts/commit/d5444b6f1607cbd87778bbe7e7d2bb0dc8df3a55))
- **web-scripts:** Upgrade to ESLint ^6.8.0 ([d0c37e9](https://github.com/spotify/web-scripts/commit/d0c37e9b63e4260eeaffda632a8d0840a793fec4))

### BREAKING CHANGES

- Minimum Node version has been increased
- **web-scripts:** Users of web-scripts that rely on ESLint 5 will see unexpected linting errors.

## [3.3.1](https://github.com/spotify/web-scripts/compare/v3.3.0...v3.3.1) (2020-01-03)

### Bug Fixes

- **create-web-scripts-library:** bump template ([c7516fa](https://github.com/spotify/web-scripts/commit/c7516fa2cc0ca2c153a6006e8ef1c1d88972933a))

# [3.3.0](https://github.com/spotify/web-scripts/compare/v3.2.0...v3.3.0) (2020-01-03)

### Features

- **deps:** yarn upgrade ([1b49fd8](https://github.com/spotify/web-scripts/commit/1b49fd84fcf23eb992dea9ac6cf08bf20b35270e))

# [3.2.0](https://github.com/spotify/web-scripts/compare/v3.1.0...v3.2.0) (2020-01-02)

### Features

- **postinstall:** move preinstall to postinstall; make CI-safe ([97aa021](https://github.com/spotify/web-scripts/commit/97aa021))
- **web-scripts:** web-scripts preinstall ([#73](https://github.com/spotify/web-scripts/issues/73)) ([f043658](https://github.com/spotify/web-scripts/commit/f043658))
- **web-scripts preinstall:** Add test coverage and use enum options ([aaed187](https://github.com/spotify/web-scripts/commit/aaed187)), closes [#73](https://github.com/spotify/web-scripts/issues/73)

# [3.1.0](https://github.com/spotify/web-scripts/compare/v3.0.1...v3.1.0) (2020-01-02)

### Bug Fixes

- stylecheck should use implicit config ([9c9a88c](https://github.com/spotify/web-scripts/commit/9c9a88c))

### Features

- **web-scripts lint:** Adds optional --stylecheck to lint command ([0c3b687](https://github.com/spotify/web-scripts/commit/0c3b687))

## [3.0.1](https://github.com/spotify/web-scripts/compare/v3.0.0...v3.0.1) (2019-10-24)

### Bug Fixes

- **eslint-config-react:** Add `static-variables` to `react/sort-comp` ([f0526c0](https://github.com/spotify/web-scripts/commit/f0526c0))

# [3.0.0](https://github.com/spotify/web-scripts/compare/v2.1.0...v3.0.0) (2019-10-10)

### Bug Fixes

- **eslint-config:** Update typescript-eslint packages to ^2.2.0 ([bda6c5f](https://github.com/spotify/web-scripts/commit/bda6c5f))

### BREAKING CHANGES

- **eslint-config:** Major version bump

# [2.1.0](https://github.com/spotify/web-scripts/compare/v2.0.1...v2.1.0) (2019-10-10)

### Features

- use package attributes to determine lint preset ([f6151ed](https://github.com/spotify/web-scripts/commit/f6151ed)), closes [#56](https://github.com/spotify/web-scripts/issues/56)

## [2.0.1](https://github.com/spotify/web-scripts/compare/v2.0.0...v2.0.1) (2019-09-27)

### Bug Fixes

- **eslint-config-typescript:** add no-useless-constructor override ([72c6651](https://github.com/spotify/web-scripts/commit/72c6651))

# [2.0.0](https://github.com/spotify/web-scripts/compare/v1.4.0...v2.0.0) (2019-09-23)

### Features

- **eslint-config-base:** Add rule for disallowing useless constructors ([beab7ec](https://github.com/spotify/web-scripts/commit/beab7ec))
- **web-scripts:** add format script; use implicit prettier config ([e7a15b1](https://github.com/spotify/web-scripts/commit/e7a15b1))
- **web-scripts:** use Jest config in project ([a6284a6](https://github.com/spotify/web-scripts/commit/a6284a6)), closes [#39](https://github.com/spotify/web-scripts/issues/39)
- **web-scripts:** use project ESLint configs ([233ed23](https://github.com/spotify/web-scripts/commit/233ed23)), closes [#39](https://github.com/spotify/web-scripts/issues/39)

### BREAKING CHANGES

- **web-scripts:** users who have Jest configs but do not pass them will begin having that config
  applied.
- **web-scripts:** projects which have ESLint files but do not pass them to web-scripts will start
  having them automatically applied
- **eslint-config-base:** Adding a lint rule which doesn't have a fix, which means that upgrading could break
  builds due to the new rule.

# [1.4.0](https://github.com/spotify/web-scripts/compare/v1.3.0...v1.4.0) (2019-09-20)

### Features

- **eslint-config:** add prettier/react ([bfea01a](https://github.com/spotify/web-scripts/commit/bfea01a))

# [1.3.0](https://github.com/spotify/web-scripts/compare/v1.2.3...v1.3.0) (2019-08-30)

### Features

- **web-scripts:** add checkstyle to lint ([0822ae2](https://github.com/spotify/web-scripts/commit/0822ae2))

## [1.2.1](https://github.com/spotify/web-scripts/compare/v1.2.0...v1.2.1) (2019-08-30)

### Bug Fixes

- **web-scripts:** ignore TypeScript declaration files from coverage ([8bcfc7f](https://github.com/spotify/web-scripts/commit/8bcfc7f)), closes [#45](https://github.com/spotify/web-scripts/issues/45)

# [1.2.0](https://github.com/spotify/web-scripts/compare/v1.1.4...v1.2.0) (2019-07-29)

### Features

- **eslint-config:** initialize library; use in web-scripts ([d209a3f](https://github.com/spotify/web-scripts/commit/d209a3f)), closes [#40](https://github.com/spotify/web-scripts/issues/40)

## [1.1.4](https://github.com/spotify/web-scripts/compare/v1.1.3...v1.1.4) (2019-07-17)

### Bug Fixes

- Add repostiory field to package.json files ([fccd2db](https://github.com/spotify/web-scripts/commit/fccd2db))
- **deps:** fix vulnerabilities ([25c7b81](https://github.com/spotify/web-scripts/commit/25c7b81))
- **web-scripts:** allow all test options to be configured ([5750c57](https://github.com/spotify/web-scripts/commit/5750c57)), closes [#19](https://github.com/spotify/web-scripts/issues/19)

## [1.1.3](https://github.com/spotify/web-scripts/compare/v1.1.2...v1.1.3) (2019-07-02)

### Bug Fixes

- **create-web-scripts-library:** move web-scripts to devDependency ([868354d](https://github.com/spotify/web-scripts/commit/868354d))

## [1.1.2](https://github.com/spotify/web-scripts/compare/v1.1.1...v1.1.2) (2019-07-01)

### Bug Fixes

- **create-web-scripts-library:** add prepublish to release ([0323798](https://github.com/spotify/web-scripts/commit/0323798))

## [1.1.1](https://github.com/spotify/web-scripts/compare/v1.1.0...v1.1.1) (2019-07-01)

### Bug Fixes

- **create-web-scripts-library:** make sure that log output is shown ([9bff988](https://github.com/spotify/web-scripts/commit/9bff988))

# [1.1.0](https://github.com/spotify/web-scripts/compare/v1.0.2...v1.1.0) (2019-07-01)

### Bug Fixes

- support ESLint 6 in our configs ([59341e3](https://github.com/spotify/web-scripts/commit/59341e3))
- Updates engines field to node >=10 ([b3b4f58](https://github.com/spotify/web-scripts/commit/b3b4f58))

### Features

- **create-web-scripts-library:** implement cli and script ([ce381f3](https://github.com/spotify/web-scripts/commit/ce381f3))

## [1.0.2](https://github.com/spotify/web-scripts/compare/v1.0.1...v1.0.2) (2019-06-26)

### Bug Fixes

- update dependencies for peerDependency warnings ([eceff7c](https://github.com/spotify/web-scripts/commit/eceff7c))

## [1.0.1](https://github.com/spotify/web-scripts/compare/v1.0.0...v1.0.1) (2019-06-24)

### Bug Fixes

- **web-scripts:** drop the `fix` command ([eb0d61d](https://github.com/spotify/web-scripts/commit/eb0d61d))
