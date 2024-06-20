# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur

- Use [vue-tsc](https://github.com/vuejs/language-tools/tree/master/packages/tsc) for performing the same type checking from the command line, or for generating d.ts files for SFCs.

## Storybook 7 を Vue 3 + TypeScript ではじめよう！
https://zenn.dev/sa2knight/books/storybook-7-with-vue-3/viewer/summary


## ライブラリの導入

```bash
yarn add -D storybook
yarn add -D @storybook/vue3-vite
yarn add -D @storybook/addon-controls
yarn add -D @storybook/addon-actions
yarn add -D @storybook/addon-viewport
yarn add -D @storybook/addon-backgrounds
yarn add -D @storybook/addon-measure @storybook/addon-outline
yarn add -D @storybook/addon-interactions @storybook/testing-library
yarn playwright install
yarn playwright install-deps 
yarn add -D @storybook/jest
yarn add vue-i18n
yarn add -D @storybook/addon-toolbars
yarn add pinia
yarn add vue-router
```

## storybook起動

```
arn storybook dev --port 6006
```

## テストランナー起動

```
yarn test-storybook --url http://localhost:6006
```