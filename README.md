# mybucket

这是一个个人维护的 [Scoop](https://scoop.sh/) bucket，用于收录和安装一些未放入官方 bucket 的 Windows 应用。

远程仓库地址：

```powershell
https://github.com/llxo/mybucket
```

## 添加 bucket

确保已安装 Scoop 后，执行：

```powershell
scoop bucket add mybucket https://github.com/llxo/mybucket
```

添加完成后，可以安装本仓库中的应用：

```powershell
scoop install md-preview
scoop install eaappemulater
scoop install tiez-clipboard
scoop install floral-notepaper
scoop install netcatty
```

## 已收录应用

| 应用 | 简介 | 上游项目 |
| --- | --- | --- |
| `md-preview` | 轻量级 Markdown 预览应用，基于 Rust 和原生 WebView。 | <https://github.com/vorojar/md-preview> |
| `eaappemulater` | EA app 模拟器和轻量级 EA Desktop/Origin 替代工具。 | <https://github.com/CrazyZhang666/EAappEmulater> |
| `tiez-clipboard` | 跨平台剪贴板管理器，支持历史、标签、同步和隐私保护。 | <https://github.com/jimuzhe/tiez-clipboard> |
| `floral-notepaper` | 轻量优雅的桌面便签工具，支持 Markdown 编辑与预览。 | <https://github.com/Achilng/floral-notepaper> |
| `netcatty` | 现代跨平台 netcat 替代工具，具备增强的网络调试和数据传输功能。 | <https://github.com/binaricat/Netcatty> |

## 常用命令

```powershell
# 更新 bucket 索引
scoop update

# 更新已安装应用
scoop update *

# 查看 bucket 列表
scoop bucket list
```
