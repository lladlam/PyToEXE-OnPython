# PyToEXE-OnPython
基于Python的Py文件转exe软件，支持各种生成方式
<img src="https://count.i80k.com/api/counter?name=PyToEXE-OnPython&theme=rule34&length=7&scale=1&offset=0&align=center&pixelate=on&darkmode=auto" alt="PyToEXE-OnPython" />
# Python转EXE工具

这是一个使用PyInstaller将Python脚本转换为Windows可执行文件（.exe）的图形界面工具。

## 功能特点

- 图形用户界面，操作简单直观
- 支持多种PyInstaller选项配置
- 自动检测并安装PyInstaller依赖
- 实时显示转换过程日志
- 支持添加自定义图标

## 依赖要求

- Python 3.x
- tkinter（Python标准库，通常已预装）
- PyInstaller（程序会自动安装）

## 使用方法

1. 运行`py_to_exe_converter.py`启动程序
2. 点击"浏览"按钮选择需要转换的Python文件（.py）
3. 在"转换选项"区域配置打包选项：
   - 打包为单个文件：生成单个exe文件
   - 打包为目录：生成包含exe文件的目录
   - 显示/不显示控制台窗口：选择是否显示黑色控制台窗口
   - 添加图标：选择.ico格式的图标文件
4. 点击"转换为EXE"开始转换
5. 转换完成后，exe文件将出现在原Python文件所在目录的`dist`文件夹中

## 注意事项

- 转换过程可能需要一些时间，请耐心等待
- 如果没有安装PyInstaller，程序会自动安装
- 建议在转换前确保Python环境正常
- 生成的exe文件可能被部分杀毒软件误报，请添加信任

## 原理

该工具使用PyInstaller库将Python脚本及其依赖项打包成独立的Windows可执行文件，使得没有安装Python环境的用户也能运行程序。
