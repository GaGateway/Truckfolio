# Truckfolio beta

**为卡车摄影爱好者制作。**

Truckfolio 是一款用于整理 **卡车摄影作品** 的本地图鉴工具。  
名字来自 **Truck + Portfolio**。

它最初为个人拍车摄影整理需求而制作，后来因为用着还挺顺手，于是顺便公开发布给有类似需求的人。

> 当前版本：**v0.3.7 Beta**  
> 当前软件界面仅提供 **中文**。  
> Beta 阶段仍可能偶尔有一些小虫子乱爬 🐛

![Truckfolio 整体图鉴](assets/screenshots/library.png)

## 特点

### 📷 为卡车摄影而做

Truckfolio 的信息结构围绕卡车摄影设计，可以为每辆车记录：

- 拍摄地点
- 品牌
- 系列
- 车型
- 公司
- 车牌
- 马力
- 编号
- 底盘
- 备注

同一辆车可以关联多张照片，并设置封面与调整照片顺序。

### 🗂 本地图鉴

Truckfolio 使用本地索引管理摄影作品。

添加照片时，软件只记录原始文件的位置：

- 不复制原图
- 不移动原图
- 不修改原图

照片仍然留在原来的文件夹中。

![车辆详情](assets/screenshots/vehicle-detail.png)

### 🔎 搜索与筛选

可以快速搜索：

- 品牌
- 公司
- 车牌
- 编号
- 拍摄地点

整体图鉴还支持按照：

- 品牌
- 系列
- 底盘

进行组合筛选，并可以调整卡片大小和排序方式。

### 📊 拍摄统计

Truckfolio 会根据已经整理的车辆生成本地摄影统计，包括：

- 已记录车辆数量
- 已整理照片数量
- 拍车足迹
- 拍摄过的品牌
- 拍摄过的系列
- 拍摄过的公司
- 拍摄过的底盘类型

统计项目可以直接进入对应的图鉴结果。

![拍摄统计](assets/screenshots/statistics.png)

### 🖼 多图管理

每辆车可以保存多张摄影作品，并支持：

- 添加本地照片
- 设置封面
- 拖动调整顺序
- 查看照片信息
- 删除单张关联照片

![编辑车辆](assets/screenshots/edit-vehicle.png)

### 🧰 其他功能

- 大图 / 中图 / 小图三种图鉴密度
- 批量选择车辆
- 重复照片检测
- 原图缺失检查与重新索引
- 本地缓存与存储目录管理
- 浅色 / 深色 / 跟随系统主题
- 中英文品牌名称显示切换
- 车辆信息文本复制与粘贴

---

## 下载

请前往 GitHub **Releases** 下载最新版本。

| 平台 | 安装包 |
| --- | --- |
| macOS | `.dmg` |
| Windows | `.msi` |

### 系统提示

目前发布的安装包 **没有进行代码签名**。

因此，macOS 或 Windows 在首次安装 / 打开 Truckfolio 时，可能会显示“无法验证开发者”“未知发布者”或类似的安全提示。

请仅从本项目的官方 GitHub Releases 页面下载安装包。

#### macOS

如果 macOS 阻止打开 Truckfolio，可以在尝试启动应用后进入：

**系统设置 → 隐私与安全性 → 仍要打开**

然后再次确认启动。

#### Windows

Windows SmartScreen 可能会对尚未建立信誉的应用显示提示。请确认安装包来自本项目的 GitHub Releases 页面后，再决定是否继续运行。

---

## 关于 Beta

Truckfolio 目前仍处于 **Beta** 阶段。

主要功能已经可以正常使用，但仍可能存在：

- 偶发 Bug
- 特定环境下的兼容性问题
- 尚未发现的界面或数据异常

如果遇到奇怪的小虫子，欢迎通过 GitHub Issues 提交问题。

---

## 数据与隐私

Truckfolio 是一个本地应用。

车辆资料、照片索引以及应用数据均保存在本地。Truckfolio 不需要上传摄影作品来建立图鉴。

删除 Truckfolio 中的图鉴记录，也不会删除对应的原始照片文件。

---

## 关于名字

**Truckfolio = Truck + Portfolio**

一个专门拿来装卡车摄影作品的小图鉴。

---

## Credits

**Design — x64**  
**Development — GaGateway**

---

## License

Truckfolio 当前不是开源软件。

Copyright © 2026 GaGateway. All rights reserved.

未经许可，不得复制、修改、重新发布或分发 Truckfolio 的源代码。

---

# English

## Truckfolio beta

**Built for truck photography enthusiasts.**

Truckfolio is a local catalog application designed for organizing **truck photography**.

The name comes from **Truck + Portfolio**.

Originally created for personal truck-photography organization, Truckfolio eventually became useful enough to be released publicly for others with similar needs.

> Current version: **v0.3.7 Beta**  
> The application interface is currently available in **Chinese only**.  
> As a Beta release, a few little bugs may still be crawling around. 🐛

## Features

### 📷 Designed around truck photography

Truckfolio provides dedicated fields for recording:

- Shooting location
- Brand
- Series
- Model
- Company
- License plate
- Horsepower
- Fleet number
- Chassis configuration
- Notes

Multiple photos can be associated with the same truck, with support for choosing a cover image and rearranging photo order.

### 🗂 Local photo catalog

Truckfolio works as a local index for your photography collection.

When photos are added, Truckfolio only records the location of the original files.

It does **not**:

- Copy the original photos
- Move the original photos
- Modify the original photos

Your images stay exactly where they already are.

### 🔎 Search and filtering

Truckfolio can search across:

- Brand
- Company
- License plate
- Fleet number
- Shooting location

The main catalog also supports combined filtering by:

- Brand
- Series
- Chassis configuration

Card size and sorting options can also be adjusted.

### 📊 Photography statistics

Truckfolio automatically generates local statistics from your catalog, including:

- Number of recorded trucks
- Number of indexed photos
- Photography locations
- Brands photographed
- Series photographed
- Companies photographed
- Chassis configurations photographed

Statistics can also be used to jump directly into matching catalog results.

### 🖼 Multi-photo management

Each truck entry can contain multiple photographs, with support for:

- Adding local photos
- Choosing a cover image
- Drag-and-drop ordering
- Viewing photo information
- Removing individual photo associations

### 🧰 Additional features

- Large / Medium / Small catalog card sizes
- Batch vehicle selection
- Duplicate-photo detection
- Missing-file detection and re-indexing
- Local cache and storage-directory management
- Light / Dark / System theme
- Chinese / English brand-name display
- Copying and pasting structured vehicle information

---

## Download

Download the latest version from **GitHub Releases**.

| Platform | Package |
| --- | --- |
| macOS | `.dmg` |
| Windows | `.msi` |

### Installation notice

Current Truckfolio builds are **not code-signed**.

Because of this, macOS or Windows may display an unidentified developer, unknown publisher, or similar security warning when Truckfolio is installed or opened for the first time.

Only download Truckfolio from the official GitHub Releases page of this project.

#### macOS

If macOS prevents Truckfolio from opening, try launching it once and then go to:

**System Settings → Privacy & Security → Open Anyway**

Confirm the prompt to launch the application.

#### Windows

Windows SmartScreen may display a warning for an application that has not yet established reputation. Verify that the installer came from this project's GitHub Releases page before deciding whether to continue.

---

## Beta status

Truckfolio is currently in **Beta**.

The main functionality is usable, but the application may still contain:

- Occasional bugs
- Compatibility issues in specific environments
- Undiscovered interface or data-related problems

If you find a strange little bug, feel free to report it through GitHub Issues.

---

## Data & Privacy

Truckfolio is a local application.

Vehicle information, photo indexes, and application data are stored locally. Truckfolio does not require uploading your photography collection in order to build the catalog.

Removing a catalog entry from Truckfolio does not delete the corresponding original photo files.

---

## About the name

**Truckfolio = Truck + Portfolio**

A little catalog made specifically for truck photography.

---

## Credits

**Design — x64**  
**Development — GaGateway**

---

## License

Truckfolio is currently proprietary software and is not open source.

Copyright © 2026 GaGateway. All rights reserved.

The Truckfolio source code may not be copied, modified, republished, or redistributed without permission.
