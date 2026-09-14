# AIWritingStudio Windows 安装包

本仓库保存 AICreationStudio 的 Windows x64 安装说明和校验信息。
安装包请从 [GitHub Releases](https://github.com/jinweechen/AIWritingStudio_Release/releases) 下载。

## 版本

- 版本：`0.2.0`
- 构建来源：`AICreationStudio/main@1f4426481fe4594fd2706849ef6ee5bbd66da816`
- 平台：Windows x64
- 安装程序语言：简体中文

## 安装说明

### 推荐方式：使用安装程序

1. 从 [v0.2.0 Release](https://github.com/jinweechen/AIWritingStudio_Release/releases/tag/v0.2.0) 下载 `AICreationStudio_0.2.0_x64-setup.exe`。
2. 双击安装程序，按照 Windows 安装向导完成安装。
3. 安装完成后，从开始菜单或桌面快捷方式启动 AICreationStudio。

### 使用 MSI 安装包

企业部署或需要使用 Windows Installer 时，可在同一 Release 中下载
`AICreationStudio_0.2.0_x64_zh-CN.msi`。该安装包的安装界面为简体中文；双击该文件即可启动安装，也可以交给系统部署工具安装。

如果 Windows 显示安全提示，请先确认文件来源和 SHA-256 校验值，再选择继续运行。

## 文件校验

安装包的 SHA-256 值见 [`SHA256SUMS.txt`](SHA256SUMS.txt)。下载 Release 附件后，将校验文件和安装包放在同一目录，在 PowerShell 中执行：

```powershell
Get-FileHash .\AICreationStudio_0.2.0_x64-setup.exe -Algorithm SHA256
Get-FileHash .\AICreationStudio_0.2.0_x64_zh-CN.msi -Algorithm SHA256
```
