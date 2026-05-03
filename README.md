# BlockGPT Resource

[![Publish npm package](https://github.com/madfire/blockgpt-resource/actions/workflows/publish.yml/badge.svg)](https://github.com/madfire/blockgpt-resource/actions/workflows/publish.yml)
![GitHub](https://img.shields.io/github/license/madfire/blockgpt-resource)

BlockGPT Resource provides the local resource server and update logic used by BlockGPT desktop experiences.

## What it does

- serves external resources required by BlockGPT desktop products
- checks resource versions
- downloads and updates packaged resources
- supports GitHub release based resource distribution

## Start locally

```bash
npm install
npm run fetch
npm start
```

## Test resource updates

```bash
npm test
```

## Product role

This repository helps BlockGPT deliver a smoother classroom and lab experience by keeping device descriptors, extension metadata, and supporting assets available locally.
