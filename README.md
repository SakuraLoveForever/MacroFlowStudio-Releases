# MacroFlow Studio

MacroFlow Studio 是 Windows 键鼠录制与自动化工具。你可以录制操作、编辑脚本，用图像或离线 OCR 判断状态，并用工作流串联任务。

## 下载和运行

1. 打开[最新版本](https://github.com/SakuraLoveForever/MacroFlowStudio-Releases/releases/latest)，下载 Assets 中的 `MacroFlowStudio_*_win64.zip`。
2. 解压整个 ZIP 到一个可写目录。将 `rapidocr_ocr/` 和随包文件保留在 `MacroFlowStudio.exe` 所在目录。
3. 双击 `MacroFlowStudio.exe`。在「脚本编辑」中绑定目标窗口，用 `F8` 开始或结束录制，保存后按 `F9` 回放。按 `F12` 停止。

适用于 64 位 Windows 10 和 Windows 11。使用发布包无需另装 Python。首次使用 OCR 时，应用会加载随包提供的本地模型。

## 更新

解压新版到新目录，再迁移需要保留的脚本、工作流和自定义图片。使用前先确认版本和下载项与对应发布说明一致。

此仓库提供下载和使用说明。GitHub 在每个 Release 下自动生成的 Source code 归档只包含此说明仓库在对应标签上的文件。可运行的软件在单独上传的 Windows ZIP 中。
