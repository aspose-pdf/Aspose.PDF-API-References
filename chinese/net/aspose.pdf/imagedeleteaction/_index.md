---
title: "枚举 ImageDeleteAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.ImageDeleteAction 枚举。当图像对象从集合中移除时执行的操作。如果图像对象被移除"
type: docs
weight: 6000
url: /zh/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

当图像对象从集合中移除时执行的操作。如果图像对象被移除

```csharp
public enum ImageDeleteAction
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| KeepContents | `0` | 图像将从集合中移除。如果页面内容包含对该图像的引用，则这些引用不会被移除。文档可能会变得无效。 |
| None | `1` | 图像将从集合和页面内容中移除，但图像对象不会被删除。文件大小不会减少。 |
| ForceDelete | `2` | 图像将从集合中移除，图像对象也将从文档中移除。如果同一对象上存在其他引用，文档可能会损坏。 |
| Check | `3` | 图像将从集合中移除，且仅在没有其他页面对该图像的引用时才会从文档中移除。与 ForceDelete 选项相比，这可能需要更多时间。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


