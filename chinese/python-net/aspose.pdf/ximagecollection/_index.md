---
title: "XImageCollection"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示 XImage 集合的类。"
type: docs
weight: 1690
url: /zh/python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

表示 XImage 集合的类。

XImageCollection 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_synchronized | 如果对象已同步，则返回 true。 |
| sync_root | 返回同步对象。 |
| names | 获取图像名称数组。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 根据索引从集合中获取图像。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| add(image) | 向 Image 列表添加新图像。此方法将图像作为对同一 PdfObject 的引用添加（可减小文件大小）。 |
| add(image) | 将实体添加到集合末尾，以便可以通过最后的索引访问该实体。 |
| add(image, filter_type) | 将实体添加到集合末尾，以便可以通过最后的索引访问该实体。 |
| add(image, quality) | 将实体添加到集合末尾，以便可以通过最后的索引访问该实体。 |
| delete(index) | 通过索引从集合中移除项目。 |
| delete(index, action) | 通过索引从集合中移除图像，并执行 action 参数指定的操作。 |
| delete(name) | 通过名称从集合中移除项目。 |
| delete(name, action) | 通过名称从集合中移除项目。 |
| delete() | 通过索引从集合中移除项目。 |
| replace(index, stream) | 将集合中的图像替换为另一图像。 |
| replace(index, stream, quality, is_black_and_white) | 将集合中的图像替换为另一图像。 |
| replace(index, stream, quality) | 将集合中的图像替换为另一图像。 |
| get_image_name(image) | 返回图像列表中的名称，该名称是给定图像的键。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

