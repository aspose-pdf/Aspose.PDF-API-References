---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp 类。表示印章的类
type: docs
weight: 4720
url: /zh/net/aspose.pdf.facades/stamp/
---
## 印章类

表示印章的类。

```csharp
public sealed class Stamp
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Stamp](stamp/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | 获取或设置一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。 |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 获取或设置背景状态。如果为 true，印章将作为被印章页面的背景放置。默认值为 false。 |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | 获取或设置印章的透明度。 |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | 获取或设置页码。 |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | 获取或设置将受到印章影响的页面编号数组。如果 Pages = null，则文档的所有页面都受到影响。 |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 获取或设置图像印章的质量（以百分比表示）。有效值为 0..100%。 |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | 获取或设置印章的旋转角度（以度为单位）。 |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | 获取或设置印章的标识符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | 设置将用作印章的图像。 |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | 将图像设置为印章。 |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | 将文本设置为印章。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | 设置将用作印章的 PDF 文件和页面编号。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | 设置将用作印章的 PDF 文件和页面编号。 |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | 设置印章文本的文本状态。 |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 设置图像印章的大小。图像将根据指定的值进行缩放。 |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | 设置印章将在页面上放置的位置。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)