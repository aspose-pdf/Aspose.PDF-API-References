---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction 枚举。当图像从集合中移除时，对图像对象执行的操作。如果图像对象被移除
type: docs
weight: 5870
url: /zh/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction 枚举

当图像从集合中移除时，对图像对象执行的操作。如果图像对象被移除

```csharp
public enum ImageDeleteAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| KeepContents | `0` | 图像将从集合中移除。如果页面内容包含对图像的引用，则这些引用不会被移除。文档可能会变得无效。 |
| None | `1` | 图像将从集合和页面内容中移除，但图像对象不会被删除。文件大小不会减少。 |
| ForceDelete | `2` | 图像将从集合中移除，图像对象将从文档中移除。如果同一对象存在其他引用，文档可能会损坏。 |
| Check | `3` | 图像将从集合中移除，只有在没有其他页面对图像的引用时，图像对象才会被移除。这可能需要比 ForceDelete 选项更多的时间。 |

### 另见

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)