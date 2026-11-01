# Truckfolio

**给拍卡车的人做的本地图鉴。**

Truckfolio = **Truck + Portfolio**，一个专门用来整理卡车摄影作品的小工具。

最早是给自己拍车用的，后来发现还挺顺手，就顺便发出来了 ✧

> 当前版本：**v0.4.1**
> 界面语言：**中文 / English**
> 遇到小虫子的话，欢迎来 [GitHub Issues](https://github.com/GaGateway/Truckfolio/issues) 抓给我们 🐛

![Truckfolio 整体图鉴](assets/screenshots/library.png)

## 它是什么？

**纯本地的摄影作品图鉴**，不是云图库。

- ✅ 我自己拍了一堆车，想要一个软件来整理这些摄影作品，看看我一共拍了多少车
- ❌ 我想要一个像 JetPhotos 那样的可以浏览大家作品的卡车云图库

## 功能

### 📷 围绕卡车摄影设计

每辆车可以记录：拍摄地点、品牌、系列、车型、公司、车牌、马力、编号、底盘、备注。

同一辆车支持关联多张照片，可以设封面、调顺序。

### 🚛 内置品牌与车型数据库

Truckfolio 预置了常见卡车品牌和车型数据（Scania、Mercedes-Benz、MAN、Volvo、DAF 等），选车型时可以直接从预设里挑，也可以手动填写任何自定义内容。

输入品牌名称时支持自动识别，也可以手动锁定选择。品牌数据库随版本更新持续补充。

### 🗂 本地索引，原图保持原样

添加照片时，Truckfolio 只索引原始文件的位置，原图完全保持原样，留在它本来的文件夹里。

需要时可以直接从 Truckfolio 定位到原始文件。

### 🔎 搜索与筛选

支持按品牌、公司、车牌、编号、拍摄地点快速搜索。

图鉴还支持按品牌 / 系列 / 底盘组合筛选，可以调整卡片大小和排序方式。

### 📊 拍摄统计

根据你整理的车辆自动生成本地统计：车辆数、照片数、拍车足迹、拍过的品牌 / 系列 / 公司 / 底盘类型。

每一项都可以直接跳进对应的图鉴结果。

![拍摄统计](assets/screenshots/statistics.png)

### 🖼 多图管理

每辆车可以保存多张照片，支持设封面、拖动排序、方向键切换、定位原图、删除单张关联。

删除车辆记录时缓存缩略图一起清理，原始照片不受影响。

![编辑车辆](assets/screenshots/edit-vehicle.png)

### 🔍 照片查看器

支持滚轮缩放、拖动平移、双击缩放、缩放按钮控制，macOS 还支持触控板双指平移和捏合缩放。

### 🧰 还有这些

- 大图 / 中图 / 小图三种图鉴密度
- 批量选择车辆
- 重复照片检测
- 原图缺失检查与重新索引
- 本地缓存与存储目录管理
- 浅色 / 深色 / 跟随系统主题
- 中英文品牌名称显示切换
- 中文 / English 界面切换
- 车辆信息复制 & 粘贴
- 导入时未知或空白字段不会覆盖已有内容
- 大量照片的添加与浏览流畅度优化（尤其 Windows）
- 缩略图保留原图色彩，边缘显示优化

---

## 下载

前往 GitHub **[Releases](https://github.com/GaGateway/Truckfolio/releases/latest)** 下载最新版本。

| 平台 | 安装包 |
| --- | --- |
| macOS | `.dmg`（Apple Silicon） |
| Windows | `.exe`（x64） |

### 关于安装提示

当前安装包**没有代码签名**，首次安装时系统可能弹出"无法验证开发者"之类的安全提示。

请只从本项目的 [GitHub Releases](https://github.com/GaGateway/Truckfolio/releases/latest) 页面下载。

<details>
<summary><b>macOS 遇到安全提示？</b></summary>

如果 macOS 阻止打开，尝试启动一次后前往：

**系统设置 → 隐私与安全性 → 仍要打开**

如果提示 **"已损坏，无法打开"** 或要求移到废纸篓：确认来源是官方 GitHub Releases，将 Truckfolio 拖入**应用程序**文件夹，然后在终端运行：

```bash
xattr -dr com.apple.quarantine /Applications/Truckfolio.app
```

如果应用不在"应用程序"文件夹里，可以输入 `xattr -dr com.apple.quarantine `（保留末尾空格），然后把 `Truckfolio.app` 直接拖进终端窗口，回车。

</details>

<details>
<summary><b>Windows SmartScreen 弹窗？</b></summary>

SmartScreen 可能会对尚未建立信誉的应用弹出警告。确认安装包来自本项目的 GitHub Releases 页面后继续运行即可。

</details>

---

## 数据与隐私

Truckfolio 是纯本地应用。车辆信息、照片索引、应用数据全部保存在本地，不需要上传任何东西。

删除图鉴记录不会删除原始照片。

---

## Credits

**Design — x64**
**Development — GaGateway**

---

## License

Truckfolio 当前为非开源软件。

Copyright © 2026 GaGateway. All rights reserved.
未经许可，不得复制、修改、重新发布或分发源代码。

---

# English

**A local catalog for truck photography.**

Truckfolio = **Truck + Portfolio** — a small tool built specifically for organizing truck photography.

Started as a personal project, then turned out useful enough to share ✧

> Current version: **v0.4.1**
> Interface language: **Chinese / English**
> Found a bug? Catch it for us on [GitHub Issues](https://github.com/GaGateway/Truckfolio/issues) 🐛

![Truckfolio library](assets/screenshots/library-en.png)

## What is it?

**A fully local photography catalog**, not a cloud gallery.

- ✅ I've shot a lot of trucks and want an app to organize my work
- ❌ I want a JetPhotos-style cloud gallery to browse everyone's photos

## Features

### 📷 Built around truck photography

Record for each truck: shooting location, brand, series, model, company, license plate, horsepower, fleet number, chassis configuration, and notes.

Multiple photos per truck, with cover selection and drag-to-reorder.

### 🚛 Built-in brand & model database

Truckfolio comes with presets for common truck brands and models (Scania, Mercedes-Benz, MAN, Volvo, DAF, and more). Pick from the presets when recording a truck, or type in anything custom.

Brand names are automatically recognized as you type, and you can manually lock a selection. The database grows with each release.

### 🗂 Local index, originals stay as they are

When photos are added, Truckfolio only indexes the location of the original files — your images stay exactly where they already are, completely untouched.

You can reveal the original file in its folder at any time from within Truckfolio.

### 🔎 Search & filter

Quick search across brand, company, license plate, fleet number, and shooting location.

The catalog also supports combined filtering by brand / series / chassis, with adjustable card sizes and sort options.

### 📊 Photography statistics

Auto-generated local stats from your catalog: truck count, photo count, shooting locations, and breakdowns by brand, series, company, and chassis type.

Each stat links directly to matching catalog results.

![Photography statistics](assets/screenshots/statistics-en.png)

### 🖼 Multi-photo management

Each truck entry holds multiple photos with support for cover selection, drag-to-reorder, arrow-key navigation, revealing originals, and removing individual associations.

Deleting a vehicle entry cleans up cached thumbnails automatically. Original photos are never touched.

![Edit vehicle](assets/screenshots/edit-vehicle-en.png)

### 🔍 Photo viewer

Mouse wheel zoom, drag-to-pan, double-click zoom, zoom controls, smooth boundary behavior, and macOS trackpad support (two-finger pan, pinch-to-zoom).

### 🧰 And more

- Large / Medium / Small catalog card sizes
- Batch vehicle selection
- Duplicate-photo detection
- Missing-file detection & re-indexing
- Local cache and storage directory management
- Light / Dark / System theme
- Chinese / English brand name display
- Chinese / English interface switching
- Copy & paste structured vehicle info
- Unknown or empty fields never overwrite existing values on import
- Smoother importing and browsing for large collections, especially on Windows
- Improved thumbnail edge rendering with faithful color

---

## Download

Get the latest version from **[GitHub Releases](https://github.com/GaGateway/Truckfolio/releases/latest)**.

| Platform | Package |
| --- | --- |
| macOS | `.dmg` (Apple Silicon) |
| Windows | `.exe` (x64) |

### Installation notice

Current builds are **not code-signed**, so your system may show a security warning on first launch.

Only download Truckfolio from this project's [GitHub Releases](https://github.com/GaGateway/Truckfolio/releases/latest) page.

<details>
<summary><b>macOS security prompt?</b></summary>

If macOS blocks the app, try launching it once, then go to:

**System Settings → Privacy & Security → Open Anyway**

If macOS says **"Truckfolio is damaged and can't be opened"** or wants to move it to Trash: confirm it came from the official GitHub Releases, move Truckfolio into **Applications**, then run in Terminal:

```bash
xattr -dr com.apple.quarantine /Applications/Truckfolio.app
```

If Truckfolio is stored elsewhere, type `xattr -dr com.apple.quarantine ` (keep the trailing space), drag `Truckfolio.app` into the Terminal window, and press Enter.

</details>

<details>
<summary><b>Windows SmartScreen?</b></summary>

SmartScreen may flag an app that hasn't built up reputation yet. Verify the installer came from this project's GitHub Releases page, then proceed.

</details>

---

## Data & Privacy

Truckfolio is a local application. Vehicle info, photo indexes, and app data are all stored locally — nothing needs to be uploaded.

Removing a catalog entry does not delete the original photo files.

---

## Credits

**Design — x64**
**Development — GaGateway**

---

## License

Truckfolio is currently proprietary software and is not open source.

Copyright © 2026 GaGateway. All rights reserved.
The source code may not be copied, modified, republished, or redistributed without permission.
