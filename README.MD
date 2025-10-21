![](docs/images/logo.png)

[![Downloads](https://img.shields.io/badge/dynamic/json?color=green&label=Downloads&query=totalString&url=https%3A%2F%2Fraw.githubusercontent.com%2Ftopjohnwu%2Fmagisk-files%2Fcount%2Fcount.json&cacheSeconds=1800)](https://raw.githubusercontent.com/topjohnwu/magisk-files/count/count.json)

#### 这不是 Google 官方支持的产品

## 介绍

Magisksuu 是一款用于定制 vivo 的开源软件，支持 Android 6.0 及以上版本的设备。
<br>
其主要功能如下:

- **MagiskSUU**: 为应用程序提供 root 访问权限
- **Magisk 模块**: 通过安装模块修改只读分区
- **MagiskBoot**: 最完整的 Android 启动映像解压和重新打包工具
- **Zygisk**: 在每个 Android应用程序的进程中运行代码
## 下载

[Github](https://github.com/trlefi/Magisk-suu) 是您获取 Magisksuu 下载的来源。

## 有用的链接

- [安装说明](https://topjohnwu.github.io/Magisk/install.html)
- [建筑与开发](https://topjohnwu.github.io/Magisk/build.html)
- [Magisk 文档](https://topjohnwu.github.io/Magisk/)
- [Zygisk 模块示例](https://github.com/topjohnwu/zygisk-module-sample)

## 错误报告

**仅接受来自调试版本的错误报告。**

对于安装问题，请同时上传启动映像和安装日志。<br>
对于 Magisk 问题，请上传启动 logcat 或 dmesg。<br>
对于 Magisk 应用崩溃，请记录并上传崩溃发生时的 logcat。

## 翻译贡献

Magisksuu 应用程序及其存根 APK 的默认字符串资源位于此处:

- `app/core/src/main/res/values/strings.xml`
- `app/stub/src/main/res/values/strings.xml`

翻译每一个并将它们放置在相应的位置 (`[module]/src/main/res/values-[lang]/strings.xml`).

## 执照

    Magisk, including all git submodules are free software:
    you can redistribute it and/or modify it under the terms of the
    GNU General Public License as published by the Free Software Foundation,
    either version 3 of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
