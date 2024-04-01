# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 13.0.0 (2024-04-01)

### Bug Fixes

- bindings.close() should cause a canceled read error ([#1972](https://github.com/serialport/node-serialport/issues/1972)) ([50f967e](https://github.com/serialport/node-serialport/commit/50f967e788f362da57d782829712542c8f15f8c8))
- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))
- enabling disabled tests rename all pkgs to lib ([#1941](https://github.com/serialport/node-serialport/issues/1941)) ([b1cc840](https://github.com/serialport/node-serialport/commit/b1cc840e5a101765faa2a36ef63b9fa13c83c6bc))
- learn now needs the package-lock.json files ([4b8fc24](https://github.com/serialport/node-serialport/commit/4b8fc248778b69f7afde17ab9ef791ef8867c4a5))
- npmignore should ignore .DS_Store files ([#1954](https://github.com/serialport/node-serialport/issues/1954)) ([eb6b57b](https://github.com/serialport/node-serialport/commit/eb6b57bffe33c9bc7775bb6b0fdf1081db86ebcc))
- stopbits definition and move binding-mock ([#2419](https://github.com/serialport/node-serialport/issues/2419)) ([63ec6bb](https://github.com/serialport/node-serialport/commit/63ec6bb7d6be312bcc8d0976c9780325c9898632))
- stream read not working past 1 read ([#1925](https://github.com/serialport/node-serialport/issues/1925)) ([3a13279](https://github.com/serialport/node-serialport/commit/3a132792e7021035757458c04479973b7516e2f5))
- stream required bindings-mock as a dep ([#1970](https://github.com/serialport/node-serialport/issues/1970)) ([e978b7e](https://github.com/serialport/node-serialport/commit/e978b7eb244b87a6be2ae914965adeb1f4562935))

### chore

- remove node6 support and upgrade codebase ([#1851](https://github.com/serialport/node-serialport/issues/1851)) ([d4f15c0](https://github.com/serialport/node-serialport/commit/d4f15c0a09750bdb42e5631ffc412c28b9f09174))
- upgrade packages and minimum node ([#2630](https://github.com/serialport/node-serialport/issues/2630)) ([daffa1a](https://github.com/serialport/node-serialport/commit/daffa1ae78895b3ed51db708219b312845bcd82b))

### Features

- add eslint mocha ([#1922](https://github.com/serialport/node-serialport/issues/1922)) ([afbc431](https://github.com/serialport/node-serialport/commit/afbc4312fca2c8cce369fa01d742a301f4f28fb8))
- add optional end event for piping ([#1926](https://github.com/serialport/node-serialport/issues/1926)) ([275315a](https://github.com/serialport/node-serialport/commit/275315a81fca198f1e3cd7a35c2374a14ddffeba))
- drop callback argument on SerialPort.list() ([#1943](https://github.com/serialport/node-serialport/issues/1943)) ([145b906](https://github.com/serialport/node-serialport/commit/145b906d9c3d5f9c9a6382ad6348a9b08b4b6d0a))
- Node-API migration ([#2305](https://github.com/serialport/node-serialport/issues/2305)) ([2fe7d43](https://github.com/serialport/node-serialport/commit/2fe7d434ca087f95a09ed9a3274d8b5f24e09ab4))
- platform specific open options ([#2428](https://github.com/serialport/node-serialport/issues/2428)) ([b3bead4](https://github.com/serialport/node-serialport/commit/b3bead45844498a9071c2e2edbcc2baf995bece5))
- Typescript everything ([#2406](https://github.com/serialport/node-serialport/issues/2406)) ([7ae6e51](https://github.com/serialport/node-serialport/commit/7ae6e51a84738da1999863a80f4ec8ce7acd953a))
- upgrade serialport/bindings-cpp ([#2557](https://github.com/serialport/node-serialport/issues/2557)) ([cbb344d](https://github.com/serialport/node-serialport/commit/cbb344d1f75b52ee83fca7c7598f952f8db9c956))

### BREAKING CHANGES

- drop node 12
- This release switches to NAPI which changes how many binaries are released and will potentially break your build system
- bindings now use async functions so they’ll never throw, only reject

# [12.0.0](https://github.com/serialport/node-serialport/compare/v11.0.1...v12.0.0) (2023-08-29)

**Note:** Version bump only for package @serialport/stream

## [11.0.1](https://github.com/serialport/node-serialport/compare/v11.0.0...v11.0.1) (2023-07-27)

**Note:** Version bump only for package @serialport/stream

# [11.0.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v11.0.0) (2023-04-29)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

### chore

- upgrade packages and minimum node ([#2630](https://github.com/serialport/node-serialport/issues/2630)) ([daffa1a](https://github.com/serialport/node-serialport/commit/daffa1ae78895b3ed51db708219b312845bcd82b))

### Features

- upgrade serialport/bindings-cpp ([#2557](https://github.com/serialport/node-serialport/issues/2557)) ([cbb344d](https://github.com/serialport/node-serialport/commit/cbb344d1f75b52ee83fca7c7598f952f8db9c956))

### BREAKING CHANGES

- drop node 12

# [10.5.0](https://github.com/serialport/node-serialport/compare/v10.4.0...v10.5.0) (2022-11-17)

### Bug Fixes

- **deps:** update dependency commander to v9.2.0 ([#2486](https://github.com/serialport/node-serialport/issues/2486)) ([4a14c4d](https://github.com/serialport/node-serialport/commit/4a14c4d817403c603c86be3a76c22634660a1a35))

### Features

- upgrade serialport/bindings-cpp ([4c07c80](https://github.com/serialport/node-serialport/commit/4c07c8077fe90af85b9b9d555a7a2b200c3bbb78))

# [10.3.0](https://github.com/serialport/node-serialport/compare/v10.2.2...v10.3.0) (2022-02-14)

### Features

- platform specific open options ([#2428](https://github.com/serialport/node-serialport/issues/2428)) ([b3bead4](https://github.com/serialport/node-serialport/commit/b3bead45844498a9071c2e2edbcc2baf995bece5))

## [10.2.2](https://github.com/serialport/node-serialport/compare/v10.2.1...v10.2.2) (2022-02-05)

### Bug Fixes

- stopbits definition and move binding-mock ([#2419](https://github.com/serialport/node-serialport/issues/2419)) ([63ec6bb](https://github.com/serialport/node-serialport/commit/63ec6bb7d6be312bcc8d0976c9780325c9898632))

## [10.2.1](https://github.com/serialport/node-serialport/compare/v10.2.0...v10.2.1) (2022-02-03)

**Note:** Version bump only for package @serialport/stream

# [10.2.0](https://github.com/serialport/node-serialport/compare/v10.1.0...v10.2.0) (2022-02-03)

### Features

- Typescript everything ([#2406](https://github.com/serialport/node-serialport/issues/2406)) ([7ae6e51](https://github.com/serialport/node-serialport/commit/7ae6e51a84738da1999863a80f4ec8ce7acd953a))

# [10.1.0](https://github.com/serialport/node-serialport/compare/v10.0.2...v10.1.0) (2022-01-23)

**Note:** Version bump only for package @serialport/stream

## [10.0.2](https://github.com/serialport/node-serialport/compare/v10.0.1...v10.0.2) (2022-01-08)

**Note:** Version bump only for package @serialport/stream

## [10.0.1](https://github.com/serialport/node-serialport/compare/v10.0.0...v10.0.1) (2021-12-25)

**Note:** Version bump only for package @serialport/stream

# [10.0.0](https://github.com/serialport/node-serialport/compare/v9.2.8...v10.0.0) (2021-12-11)

### Features

- Node-API migration ([#2305](https://github.com/serialport/node-serialport/issues/2305)) ([2fe7d43](https://github.com/serialport/node-serialport/commit/2fe7d434ca087f95a09ed9a3274d8b5f24e09ab4))

### BREAKING CHANGES

- This release switches to NAPI which changes how many binaries are released and will potentially break your build system

## [9.2.4](https://github.com/serialport/node-serialport/compare/v9.2.3...v9.2.4) (2021-09-28)

**Note:** Version bump only for package @serialport/stream

## [9.2.3](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.3) (2021-09-24)

**Note:** Version bump only for package @serialport/stream

## [9.2.2](https://github.com/serialport/node-serialport/compare/v9.2.1...v9.2.2) (2021-09-24)

**Note:** Version bump only for package @serialport/stream

## [9.0.7](https://github.com/serialport/node-serialport/compare/v9.0.6...v9.0.7) (2021-02-22)

**Note:** Version bump only for package @serialport/stream

## [9.0.2](https://github.com/serialport/node-serialport/compare/v9.0.1...v9.0.2) (2020-10-16)

**Note:** Version bump only for package @serialport/stream

## [9.0.1](https://github.com/serialport/node-serialport/compare/v9.0.0...v9.0.1) (2020-08-08)

**Note:** Version bump only for package @serialport/stream

# [9.0.0](https://github.com/serialport/node-serialport/compare/v8.0.8...v9.0.0) (2020-05-10)

**Note:** Version bump only for package @serialport/stream

## [8.0.6](https://github.com/serialport/node-serialport/compare/v8.0.5...v8.0.6) (2019-12-25)

### Bug Fixes

- bindings.close() should cause a canceled read error ([#1972](https://github.com/serialport/node-serialport/issues/1972)) ([50f967e](https://github.com/serialport/node-serialport/commit/50f967e788f362da57d782829712542c8f15f8c8))
- stream required bindings-mock as a dep ([#1970](https://github.com/serialport/node-serialport/issues/1970)) ([e978b7e](https://github.com/serialport/node-serialport/commit/e978b7eb244b87a6be2ae914965adeb1f4562935))
