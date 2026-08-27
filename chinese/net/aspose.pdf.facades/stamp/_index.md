---
title: "类 Stamp"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.Stamp 类。表示印章的类。"
type: docs
weight: 4840
url: /zh/net/aspose.pdf.facades/stamp/
---
## Stamp class

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
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 获取或设置背景状态。如果为 true，印章将放置在 spamped 页面 的背景中。默认设置为 false。 |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | 获取或设置印章的不透明度。 |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | 获取或设置页码。 |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | 获取或设置包含将受印章影响的页码的数组。如果 Pages = null，则文档的所有页都会受到影响。 |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 获取或设置图像印章的质量（百分比）。有效值 0..100%。 |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | 获取或设置印章的旋转角度（以度为单位）。 |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | 获取或设置印章的标识符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | 设置将用作印章的图像。 |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | 将图像设置为印章。 |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | 将文本设置为印章。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | 设置将用作印章的 PDF 文件及页码。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | 设置将用作印章的 PDF 文件及页码。 |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | 设置印章文本的文本状态。 |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 设置图像印章的大小。图像将根据指定的数值进行缩放。 |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | 设置印章将在页面上的放置位置。 |

### 另请参见

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


