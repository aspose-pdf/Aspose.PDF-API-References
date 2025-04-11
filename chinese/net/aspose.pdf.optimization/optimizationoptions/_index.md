---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions 类。描述文档优化算法的类。此类的实例可用作 OptimizeResources 方法的参数
type: docs
weight: 7980
url: /zh/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions 类

描述文档优化算法的类。此类的实例可用作 OptimizeResources() 方法的参数。

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
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | 如果为 true，则在文档优化为相等页面时将重用页面内容。 |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | 如果此标志设置为 `true`，Pdf 对象将被打包到对象流中并压缩以减少 pdf 文件大小。 |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | 描述文档中的图像是否会被压缩及压缩参数的选项集。 |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 将使用的图像编码器。 |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | 如果此标志设置为 true，将分析资源流。如果找到重复流（即流内容相等），则这些流将作为一个对象存储。这在某些情况下可以减少文档大小（例如，当同一文档被多次连接时）。 |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | 扫描级别。更深的扫描（更高的值）需要更长时间，但可能会生成更小的结果文件。默认值：10。 |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 指定图像的最大分辨率。如果图像的分辨率更高，则会进行缩放。 |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | 移除私人信息（页面片段信息）。 |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | 如果此标志设置为 true，将检查所有文档对象，并从文档中移除未使用的对象（即没有任何引用的对象）。 |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | 如果此标志设置为 true，将检查每个资源的使用情况。如果资源从未使用，则将其移除。这可能会减少文档大小，例如当页面从文档中提取时。 |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | 如果设置为 true，字体将被转换为子集。 |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | 如果设置为 true，则使字体不嵌入。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | 创建激活所有选项的优化策略。请注意，仅激活不改变文档任何功能的选项。即，图像压缩和字体取消嵌入将不会启用（可以手动嵌入）。 |

### 另请参见

* 命名空间 [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* 程序集 [Aspose.PDF](../../)