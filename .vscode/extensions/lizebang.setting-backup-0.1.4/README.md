# Setting Backup

由于国内 GitHub Gist 访问过慢，此项目由此诞生。

## Features

备份和恢复 _安装的插件_、_用户设置_、_键盘快捷键设置_。

### Usage

1. 设置备份文件存放路径 `"setting-backup.path" : "/path/to/vscode-settings.zip"`
2. `Ctrl+Alt+P` -> `Setting: Backup Settings` 备份配置
3. `Ctrl+Alt+P` -> `Setting: Restore Settings` 恢复配置

## Extension Settings

- `setting-backup.path`: 备份配置的路径（默认为 `~/vscode-settings.zip`）

## Release Notes

### 0.1.0

此项目诞生。
