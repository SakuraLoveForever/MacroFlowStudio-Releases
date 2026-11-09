# MacroFlow Studio

MacroFlow Studio 是 Windows 键鼠录制与自动化工具。你可以录制操作、编辑脚本，用图像或离线 OCR 判断状态，并用工作流串联任务。

## 下载和运行

适用于 64 位 Windows 10 和 Windows 11。软件包自带 Python 和离线 OCR 运行时。首次使用时需要从官方 PyPI 安装三个单独分发的运行库。

1. 打开[最新版本](https://github.com/SakuraLoveForever/MacroFlowStudio-Releases/releases/latest)，下载 Assets 中的 `MacroFlowStudio_*_win64.zip`。
2. 解压整个 ZIP 到可写目录。确认 `MacroFlowStudio.exe`、`_internal/` 和 `rapidocr_ocr/` 位于同一目录。
3. 下载下表的三个官方 Wheel 文件。开启 Windows 文件资源管理器的「文件扩展名」显示，把各文件的 `.whl` 后缀改为 `.zip` 后解压。把每个归档内第一层的文件夹复制到软件目录里的 `_internal/`。确认 `_internal/PySide6/`、`_internal/shiboken6/` 和 `_internal/pynput/` 都直接位于该目录内。
4. 双击 `MacroFlowStudio.exe`。在「脚本编辑」中绑定目标窗口，按 `F8` 开始或结束录制，保存后按 `F9` 回放。按 `F12` 停止。

| 官方运行库 | 下载文件 |
| --- | --- |
| PySide6 Essentials 6.12.0 | [Windows x64 Wheel](https://files.pythonhosted.org/packages/03/61/9a7e32a37b224f68506785bfb0f288d516098ec71681782d72b695a6c95d/pyside6_essentials-6.12.0-cp310-abi3-win_amd64.whl) |
| Shiboken6 6.12.0 | [Windows x64 Wheel](https://files.pythonhosted.org/packages/2a/b6/bee97e7a2edeab72aafabb46ee5adc939790a638d107860b4cad7a20e407/shiboken6-6.12.0-cp310-abi3-win_amd64.whl) |
| pynput 1.8.2 | [Wheel](https://files.pythonhosted.org/packages/6d/98/bbeb760852adb27f166ce1617f0e51aabb15f21b1e60ea703f2aed3c78ac/pynput-1.8.2-py2.py3-none-any.whl) |

## 更新

解压新版到新目录。按新版说明准备运行库，再迁移需要保留的脚本、工作流和自定义图片。保留随包的 `rapidocr_ocr/` 目录。

此仓库只保存下载和使用说明。GitHub 自动生成的 Source code 归档只含对应版本的说明文件。Windows 软件在单独上传的 ZIP 中，MacroFlow 的项目源码保存在私有仓库。
