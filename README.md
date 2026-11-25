# Material

个人通用静态资源仓库，存放 Loon、Clash 及其他代理工具相关的图片、图标和 JavaScript 文件，供其他项目直接引用。

## 目录

```text
loon/
├── images/    # Loon 图片、图标、规则配图
└── js/        # Loon 相关 JavaScript

clash/
├── images/    # Clash 图片、图标、规则配图
└── js/        # Clash 相关 JavaScript

common/
├── images/    # 不区分客户端的通用图片
└── js/        # 通用 JavaScript
```

当前上传的 4 个 Loon 图片：

- `loon/images/loon-rule-01.jpg`
- `loon/images/loon-rule-02.jpg`
- `loon/images/loon-rule-03.jpg`
- `loon/images/loon-rule-04.jpg`

## 引用方式

GitHub Raw：

```text
https://raw.githubusercontent.com/lcyan/material/main/loon/images/loon-rule-01.jpg
https://raw.githubusercontent.com/lcyan/material/main/loon/images/loon-rule-02.jpg
https://raw.githubusercontent.com/lcyan/material/main/loon/images/loon-rule-03.jpg
https://raw.githubusercontent.com/lcyan/material/main/loon/images/loon-rule-04.jpg
```

JavaScript 文件可以直接引用：

```text
https://raw.githubusercontent.com/lcyan/material/main/loon/js/example.js
```

也可以使用 jsDelivr：

```text
https://cdn.jsdelivr.net/gh/lcyan/material@main/loon/images/loon-rule-01.jpg
```

需要长期固定版本时，建议将 `main` 替换为具体的 commit SHA。

## 命名建议

- 使用小写英文、数字和短横线，例如 `loon-ai-rule.jpg`
- 不使用空格、中文或特殊符号
- Loon 资源放到 `loon/`，Clash 资源放到 `clash/`
- 不区分客户端的资源放到 `common/`
