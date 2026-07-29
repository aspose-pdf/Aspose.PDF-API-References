---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Aspose.PDF for Java API 参考"
description: "当图像对象从集合中移除时执行的操作。如果图像对象被移除"
type: docs
weight: 2290
url: /zh/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

当图像对象从集合中移除时执行的操作。如果图像对象被移除

## 字段

| 字段 | 描述 |
| --- | --- |
| [Check](#Check) | 图像将从集合中移除，且仅在其他页面没有对该图像的引用时才会移除图像对象。这可能比 ForceDelete 选项需要更多时间。 |
| [ForceDelete](#ForceDelete) | 图像将从集合中移除，且图像对象将从文档中移除。如果同一对象上存在其他引用，文档可能会损坏。 |
| [KeepContents](#KeepContents) | 图像将从集合中移除。如果页面内容包含对该图像的引用，它们将不会被移除。文档可能会变得无效。 |
| [None](#None) | 图像将从集合中以及页面内容中移除，但图像对象不会被删除。文件大小不会减小。 |

### Check {#Check}
```
public static final int Check
```

图像将从集合中移除，且仅在其他页面没有对该图像的引用时才会移除图像对象。这可能比 ForceDelete 选项需要更多时间。

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

图像将从集合中移除，且图像对象将从文档中移除。如果同一对象上存在其他引用，文档可能会损坏。

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

图像将从集合中移除。如果页面内容包含对该图像的引用，它们将不会被移除。文档可能会变得无效。

### None {#None}
```
public static final int None
```

图像将从集合中以及页面内容中移除，但图像对象不会被删除。文件大小不会减小。
