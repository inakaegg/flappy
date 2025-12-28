# flappy (Clove sample package)

Minimal Clove library for testing `clove pkg install` and `require`.

## Package ID

`inakaegg/flappy`

## Layout

```
src/inakaegg/flappy/core.clv
```

## Install

```
clove pkg install https://github.com/inakaegg/flappy --rev v0.1.0
# or (explicit)
clove pkg install https://github.com/inakaegg/flappy --pkg inakaegg/flappy --rev v0.1.0
```

## Usage

```clojure
(require inakaegg::flappy::core)
(inakaegg::flappy::core/hello)
(inakaegg::flappy::core/add 1 2)
```

## Release

Tag a commit to make a stable `--rev` target:

```
git tag v0.1.0
```
