# Loon Assets

用于存放 Loon 规则相关的图片、图标和可被其他项目直接引用的 JavaScript 静态资源。

## 目录

- `images/loon-rules/`：自己制作的 Loon 规则说明图、配图、卡片等
- `icons/`：服务或规则相关图标
- `js/`：可复用的 JavaScript 文件

## 引用方式

仓库默认分支为 `main`，可以直接使用 GitHub Raw 地址：

```text
https://raw.githubusercontent.com/lcyan/loon-assets/main/images/loon-rules/example.png
https://raw.githubusercontent.com/lcyan/loon-assets/main/icons/example.png
https://raw.githubusercontent.com/lcyan/loon-assets/main/js/example.js
```

需要长期固定版本时，建议使用具体 commit 的地址：

```text
https://raw.githubusercontent.com/lcyan/loon-assets/<commit-sha>/images/loon-rules/example.png
```

也可以使用 jsDelivr：

```text
https://cdn.jsdelivr.net/gh/lcyan/loon-assets@main/images/loon-rules/example.png
```

## 命名建议

- 文件名使用小写英文、数字和短横线，例如 `loon-ai-rule.png`
- 不要使用空格、中文或特殊符号
- 同一资源需要更新但不希望修改引用地址时，可以直接替换原文件
- 需要保证内容永久不变时，使用 commit SHA 引用

## 说明

这是个人静态资源仓库，主要服务于 Loon 规则配置及相关项目。新增资源时，请尽量同时在提交信息中说明用途。
