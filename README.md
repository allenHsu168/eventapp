# vue-project

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### db setup(macos arm64)

```
mkdir certs
docker compose up
```

### project setup

copy Eventstore/project.js -> create projecttion

### 網頁前端部分＝>

```sh
npm run dev
```

### DB 後段部分(Eventstore)=>

```sh
npm run server
```