# Gitlab CI

## commit 规范

Angular commit 规范 [`https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines`](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines)

### 提交基本格式：

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

`Type` 类型：

- `feat`：新功能（feature）
- `fix`：修补 bug
- `docs`：修改文档（documentation）
- `style`：修改格式，如标签、空格、格式化、分号等（不影响代码运行的变动）
- `refactor`：重构（即不是新增功能，也不是修改 bug 的代码变动）
- `test`：增加测试
- `chore`：构建过程或辅助工具的变动

通常 `feat` 和 `fix` 会被放入 `changelog` 中，其他(`docs`、`chore`、`style`、`refactor`、`test` )通常不会放入 `changelog` 中。

### 提交实例：

`feat: create a new feature`

### 其他：

可以安装 `vscode-commitizen` 插件，使用 `ctrl+shift+p` 或 `command+shift+p` 使用 `conventional commit` 提交代码。