# 上游版本与构建来源

## 上游项目

- 仓库：[`deepseek-ai/chat-demo`](https://github.com/deepseek-ai/chat-demo)
- 应用版本：`v0.1.1`
- 基线标签：`v0.1.1`
- 基线提交：[`5d5dd754ebc1948e977ddb880a9eb5aa25f37b4c`](https://github.com/deepseek-ai/chat-demo/commit/5d5dd754ebc1948e977ddb880a9eb5aa25f37b4c)
- 提交说明：`fix: clarify history import errors and release v0.1.1`
- 上游许可证：MIT

## 本仓库文件

`chat-demo.html` 是前端生产构建结果经单文件内联后的发布文件。页面内的主要前端依赖、CSS、字体和 Mermaid 运行时已经打包进 HTML，打开页面时不依赖外部脚本或样式 CDN。

发布文件校验值：

```text
SHA-256  3CBFCE1280A760D43099636CEF6B99BE21D697540AE26D252CB776607CE59C79
```

可在 PowerShell 中复核：

```powershell
Get-FileHash -Algorithm SHA256 .\chat-demo.html
```

或在 Linux / macOS 中复核：

```sh
sha256sum chat-demo.html
```

## 修改与发布说明

- 本仓库是对上游 `v0.1.1` 的单文件构建与展示整理，不是对上游源码的重新实现。
- `screenshots/` 中的图片仅用于展示界面和分享记录，不是应用运行所必需的资源。
- 根目录的 `index.html` 是本仓库添加的轻量跳转入口，应用本体仍为 `chat-demo.html`。
- 本仓库不是 DeepSeek 官方仓库，不包含官方背书。
- 如编写、调试或扩展应用源码，请前往上游仓库，并以对应版本的 `README`、构建配置和许可证为准。

## 许可证

上游代码采用 MIT License。完整许可证原文保存在本仓库的 [`LICENSE`](./LICENSE)。

```text
Copyright (c) 2026 DeepSeek
```

分发本构建物时应同时保留许可证和版权声明。第三方依赖继续遵循各自的许可证。
