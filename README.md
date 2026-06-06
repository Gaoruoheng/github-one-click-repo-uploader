# GitHub一键上传仓库代码工具

这是一个 Windows 本地图形化 GitHub 工具。它提供常用按钮，方便你不用手敲 Git 命令，也能把指定仓库代码一键上传到 GitHub，或者从 GitHub 下载最新代码。

当前配置默认指向 Kuma Closet 衣柜小程序项目，也可以修改配置文件复用到其他 Git 仓库。

## 功能

- `上传备份`：自动提交当前项目改动，并推送到 GitHub。
- `下载最新`：先把本地未提交改动保存到 Git stash，再从 GitHub 下载最新代码。
- `检查状态`：查看当前 Git 状态和远程仓库配置。
- `打开 GitHub`：打开配置好的 GitHub 仓库。
- `打开文件夹`：打开配置好的项目文件夹。

## 配置

如果小程序项目移动了位置，修改 `backup-tool.config.json`：

```json
{
  "projectRoot": "C:\\Users\\GaoRuoHeng\\WeChatProjects\\miniprogram-1",
  "remoteName": "origin",
  "branchName": "main",
  "repositoryUrl": "https://github.com/Gaoruoheng/-"
}
```

## 使用

双击运行：

```text
open-github-backup-tool.bat
```
