# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 13.0.0 (2024-04-01)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))
- enabling disabled tests rename all pkgs to lib ([#1941](https://github.com/serialport/node-serialport/issues/1941)) ([b1cc840](https://github.com/serialport/node-serialport/commit/b1cc840e5a101765faa2a36ef63b9fa13c83c6bc))
- improve repl ([#2425](https://github.com/serialport/node-serialport/issues/2425)) ([7538995](https://github.com/serialport/node-serialport/commit/7538995c8a9e086be20b8d12b309c41ca93e4e43))
- learn now needs the package-lock.json files ([4b8fc24](https://github.com/serialport/node-serialport/commit/4b8fc248778b69f7afde17ab9ef791ef8867c4a5))
- npmignore should ignore .DS_Store files ([#1954](https://github.com/serialport/node-serialport/issues/1954)) ([eb6b57b](https://github.com/serialport/node-serialport/commit/eb6b57bffe33c9bc7775bb6b0fdf1081db86ebcc))
- stopbits definition and move binding-mock ([#2419](https://github.com/serialport/node-serialport/issues/2419)) ([63ec6bb](https://github.com/serialport/node-serialport/commit/63ec6bb7d6be312bcc8d0976c9780325c9898632))

### chore

- remove node6 support and upgrade codebase ([#1851](https://github.com/serialport/node-serialport/issues/1851)) ([d4f15c0](https://github.com/serialport/node-serialport/commit/d4f15c0a09750bdb42e5631ffc412c28b9f09174))
- upgrade packages and minimum node ([#2630](https://github.com/serialport/node-serialport/issues/2630)) ([daffa1a](https://github.com/serialport/node-serialport/commit/daffa1ae78895b3ed51db708219b312845bcd82b))

### Features

- drop callback argument on SerialPort.list() ([#1943](https://github.com/serialport/node-serialport/issues/1943)) ([145b906](https://github.com/serialport/node-serialport/commit/145b906d9c3d5f9c9a6382ad6348a9b08b4b6d0a))
- move cli tools to their own packages ([#1664](https://github.com/serialport/node-serialport/issues/1664)) ([103498e](https://github.com/serialport/node-serialport/commit/103498e8dd1a13b36f3e730a2c397da43e138c9a)), closes [#1659](https://github.com/serialport/node-serialport/issues/1659)
- Typescript everything ([#2406](https://github.com/serialport/node-serialport/issues/2406)) ([7ae6e51](https://github.com/serialport/node-serialport/commit/7ae6e51a84738da1999863a80f4ec8ce7acd953a))

### BREAKING CHANGES

- drop node 12
- bindings now use async functions so they’ll never throw, only reject

# [12.0.0](https://github.com/serialport/node-serialport/compare/v11.0.1...v12.0.0) (2023-08-29)

**Note:** Version bump only for package @serialport/repl

## [11.0.1](https://github.com/serialport/node-serialport/compare/v11.0.0...v11.0.1) (2023-07-27)

**Note:** Version bump only for package @serialport/repl

# [11.0.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v11.0.0) (2023-04-29)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

### chore

- upgrade packages and minimum node ([#2630](https://github.com/serialport/node-serialport/issues/2630)) ([daffa1a](https://github.com/serialport/node-serialport/commit/daffa1ae78895b3ed51db708219b312845bcd82b))

### BREAKING CHANGES

- drop node 12

# [10.5.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v10.5.0) (2022-11-17)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

# [10.4.0](https://github.com/serialport/node-serialport/compare/v10.3.0...v10.4.0) (2022-03-04)

**Note:** Version bump only for package @serialport/repl

# [10.3.0](https://github.com/serialport/node-serialport/compare/v10.2.2...v10.3.0) (2022-02-14)

### Bug Fixes

- improve repl ([#2425](https://github.com/serialport/node-serialport/issues/2425)) ([7538995](https://github.com/serialport/node-serialport/commit/7538995c8a9e086be20b8d12b309c41ca93e4e43))

## [10.2.2](https://github.com/serialport/node-serialport/compare/v10.2.1...v10.2.2) (2022-02-05)

### Bug Fixes

- stopbits definition and move binding-mock ([#2419](https://github.com/serialport/node-serialport/issues/2419)) ([63ec6bb](https://github.com/serialport/node-serialport/commit/63ec6bb7d6be312bcc8d0976c9780325c9898632))

## [10.2.1](https://github.com/serialport/node-serialport/compare/v10.2.0...v10.2.1) (2022-02-03)

**Note:** Version bump only for package @serialport/repl

# [10.2.0](https://github.com/serialport/node-serialport/compare/v10.1.0...v10.2.0) (2022-02-03)

### Features

- Typescript everything ([#2406](https://github.com/serialport/node-serialport/issues/2406)) ([7ae6e51](https://github.com/serialport/node-serialport/commit/7ae6e51a84738da1999863a80f4ec8ce7acd953a))

# [10.1.0](https://github.com/serialport/node-serialport/compare/v10.0.2...v10.1.0) (2022-01-23)

**Note:** Version bump only for package @serialport/repl

## [10.0.2](https://github.com/serialport/node-serialport/compare/v10.0.1...v10.0.2) (2022-01-08)

**Note:** Version bump only for package @serialport/repl

## [10.0.1](https://github.com/serialport/node-serialport/compare/v10.0.0...v10.0.1) (2021-12-25)

**Note:** Version bump only for package @serialport/repl

# [10.0.0](https://github.com/serialport/node-serialport/compare/v9.2.8...v10.0.0) (2021-12-11)

**Note:** Version bump only for package @serialport/repl

## [9.2.8](https://github.com/serialport/node-serialport/compare/v9.2.7...v9.2.8) (2021-11-26)

**Note:** Version bump only for package @serialport/repl

## [9.2.7](https://github.com/serialport/node-serialport/compare/v9.2.5...v9.2.7) (2021-11-18)

**Note:** Version bump only for package @serialport/repl

## [9.2.6](https://github.com/serialport/node-serialport/compare/v9.2.5...v9.2.6) (2021-11-18)

**Note:** Version bump only for package @serialport/repl

## [9.2.5](https://github.com/serialport/node-serialport/compare/v9.2.4...v9.2.5) (2021-10-31)

**Note:** Version bump only for package @serialport/repl

## [9.2.4](https://github.com/serialport/node-serialport/compare/v9.2.3...v9.2.4) (2021-09-28)

**Note:** Version bump only for package @serialport/repl

## [9.2.3](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.3) (2021-09-24)

**Note:** Version bump only for package @serialport/repl

## [9.2.2](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.2) (2021-09-24)

**Note:** Version bump only for package @serialport/repl

## [9.2.1](https://github.com/serialport/node-serialport/compare/v9.2.0...v9.2.1) (2021-09-03)

**Note:** Version bump only for package @serialport/repl

# [9.2.0](https://github.com/serialport/node-serialport/compare/v9.1.0...v9.2.0) (2021-06-19)

**Note:** Version bump only for package @serialport/repl

# [9.1.0](https://github.com/serialport/node-serialport/compare/v9.0.8...v9.1.0) (2021-05-28)

**Note:** Version bump only for package @serialport/repl

## [9.0.8](https://github.com/serialport/node-serialport/compare/v9.0.9...v9.0.8) (2021-05-24)

**Note:** Version bump only for package @serialport/repl

## [9.0.7](https://github.com/serialport/node-serialport/compare/v9.0.6...v9.0.7) (2021-02-22)

**Note:** Version bump only for package @serialport/repl

## [9.0.6](https://github.com/serialport/node-serialport/compare/v9.0.5...v9.0.6) (2021-01-20)

**Note:** Version bump only for package @serialport/repl

## [9.0.4](https://github.com/serialport/node-serialport/compare/v9.0.3...v9.0.4) (2020-12-17)

**Note:** Version bump only for package @serialport/repl

## [9.0.3](https://github.com/serialport/node-serialport/compare/v9.0.2...v9.0.3) (2020-12-04)

**Note:** Version bump only for package @serialport/repl

## [9.0.2](https://github.com/serialport/node-serialport/compare/v9.0.1...v9.0.2) (2020-10-16)

**Note:** Version bump only for package @serialport/repl

## [9.0.1](https://github.com/serialport/node-serialport/compare/v9.0.0...v9.0.1) (2020-08-08)

**Note:** Version bump only for package @serialport/repl

# [9.0.0](https://github.com/serialport/node-serialport/compare/v8.0.8...v9.0.0) (2020-05-10)

**Note:** Version bump only for package @serialport/repl

## [8.0.8](https://github.com/serialport/node-serialport/compare/v8.0.7...v8.0.8) (2020-05-07)

**Note:** Version bump only for package @serialport/repl

## [8.0.7](https://github.com/serialport/node-serialport/compare/v8.0.6...v8.0.7) (2020-01-30)

**Note:** Version bump only for package @serialport/repl

## [8.0.6](https://github.com/serialport/node-serialport/compare/v8.0.5...v8.0.6) (2019-12-25)

**Note:** Version bump only for package @serialport/repl
