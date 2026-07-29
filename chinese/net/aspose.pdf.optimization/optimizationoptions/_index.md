---
title: "类 OptimizationOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Optimization.OptimizationOptions 类。描述文档优化算法的类。该类的实例可用作 OptimizeResources 方法的参数。"
type: docs
weight: 8120
url: /zh/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

描述文档优化算法的类。该类的实例可用作 OptimizeResources() 方法的参数。

```csharp
public class OptimizationOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | 如果为 true，则在文档针对相同页面进行优化时，页面内容将被复用。 |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | 如果此标志设置为 `true`，Pdf 对象将被打包到 Objest 流中并压缩，以减小 pdf 文件大小。 |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | 一组选项，用于描述文档中的图像是否会被压缩以及压缩的参数。 |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 将使用的图像编码方式。 |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | 如果此标志设置为 true，资源流将被分析。如果发现重复的流（即流内容相同），这些流将合并为一个对象。这在某些情况下可以减小文档大小（例如，同一文档被多次拼接时）。 |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 指定图像的最大分辨率。如果图像分辨率更高，则会被缩放。 |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | 移除私有信息（页面片段信息）。 |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | 如果此标志设置为 true，将检查所有文档对象，并删除未使用的对象（即没有任何引用的对象）。 |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | 如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未被使用，则该资源将被删除。这可能会在从文档中提取页面时减小文档大小。 |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | 如果设置为 true，字体将被转换为子集。 |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | 如果设置为 true，使字体不嵌入。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | 创建包含所有已激活选项的优化策略。请注意，仅激活不会改变文档任何功能的选项。例如，图像压缩和字体取消嵌入将不会被启用（可手动嵌入）。 |

### 另请参见

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


