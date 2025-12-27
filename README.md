# @zengzizhao/test-utils

一个轻量级的 TypeScript 工具函数库，支持 Node.js 和浏览器环境。

## 安装

```bash
npm install @zengzizhao/test-utils
# 或
pnpm add @zengzizhao/test-utils
# 或
yarn add @zengzizhao/test-utils
```

## 使用

### ES Module

```ts
import { sum, multiply } from "@zengzizhao/test-utils";

sum(1, 2); // 3
multiply(2, 3); // 6
```

### CommonJS

```js
const { sum, multiply } = require("@zengzizhao/test-utils");

sum(1, 2); // 3
multiply(2, 3); // 6
```

## API

### Math 数学函数

#### `sum(a: number, b: number): number`

计算两个数的和。

```ts
sum(1, 2); // 3
sum(-1, 1); // 0
```

#### `multiply(a: number, b: number): number`

计算两个数的乘积。

```ts
multiply(2, 3); // 6
multiply(-2, 3); // -6
```

## 特性

- 使用 TypeScript 编写，提供完整的类型定义
- 同时支持 ESM 和 CommonJS
- 支持 Node.js 和浏览器环境
- 零依赖，轻量级
