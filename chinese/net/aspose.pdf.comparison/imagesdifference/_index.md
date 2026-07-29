---
title: "类 ImagesDifference"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Comparison.ImagesDifference 类。表示比较两个 PDF 页面后的结果类"
type: docs
weight: 3340
url: /zh/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

表示比较两个 PDF 页面结果的类。

```csharp
public sealed class ImagesDifference : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | 获取差异数组。该数组类似于通过 LockBits 方法获得的原始图像数据数组。 |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | 差异的高度。 |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | 获取第一页比较的图像。该图像的像素格式为 24bpp。 |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | 差异图像数据的跨距。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | 使用指定的颜色将差异数组转换为位图图像。 |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | 在对象被销毁之前执行所有必要的清理操作。 |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | 通过将差异数组应用于源图像，返回表示目标图像的新位图。 |

### 另请参见

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


