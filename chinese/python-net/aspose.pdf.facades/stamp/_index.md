---
title: "Stamp"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示印章的类。"
type: docs
weight: 410
url: /zh/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

表示印章的类。

Stamp 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Stamp() | 初始化 Stamp 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| stamp_id | 获取或设置印章的标识符。 |
| quality | 获取或设置图像印章的质量（百分比）。有效值 0..100%。 |
| opacity | 获取或设置印章的不透明度。 |
| page_number | 获取或设置页码。 |
| pages | 获取或设置受印章影响的页面编号数组。 <br/>            如果 Pages = null，则文档的所有页面都会受到影响。 |
| rotation | 获取或设置印章的旋转角度（以度为单位）。 |
| is_background | 获取或设置背景状态。如果为 true，印章将作为页面的背景放置。<br/>            默认设置为 false。 |
| blending_space | 获取或设置一个 BlendingColorSpace 值，该值定义了一个颜色空间 <br/>            用于在页面上执行透明度和混合操作。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| bind_pdf(pdf_file, page_number) | 设置将用作印章的 PDF 文件和页码。 |
| bind_pdf(pdf_stream, page_number) | 设置将用作印章的 PDF 文件和页码。 |
| bind_image(image_file) | 将图像设置为印章。 |
| bind_image(image) | 设置将用作印章的图像。 |
| bind_logo(formatted_text) | 将文本设置为印章。 |
| bind_text_state(text_state) | 设置印章文本的文本状态。 |
| set_origin(origin_x, origin_y) | 设置印章将在页面上放置的位置。 |
| set_image_size(width, height) | 设置图像印章的大小。图像将根据指定的值进行缩放。 |

### 另请参阅

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

