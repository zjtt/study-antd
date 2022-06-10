
# 初始下载后
## 1. 安装依赖

```bash
$ pnpm install
```

## 2. 执行 style、util 构建

```
$ pnpm run build --filter @study/style
$ pnpm run build --filter @study/util
```
## 3. 创建项目
### 创建 ts 项目

```base
$ npm run create:ts
```
### 创建 js 项目

```
$ npm run create:js
```

## 4. 如果遇到cannot resolve @study/util 或者 @study/style 这类的问题，在根目录下
```
$ pnpm -F @study/util build
$ pnpm -F @study/style build
```
