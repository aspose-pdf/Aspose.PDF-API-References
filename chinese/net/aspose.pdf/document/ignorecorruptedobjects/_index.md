---
title: IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API 参考
description: 获取或设置忽略源文件中错误的标志 当源文档中的页面复制到目标文档中时如果源文件中的某些对象在此标志为假时损坏则复制过程将停止异常  示例dest.Pages.Addsrc.Pages 如果此标志设置为 true则损坏的对象将被替换为空值 默认情况下true.
type: docs
weight: 260
url: /zh/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

获取或设置忽略源文件中错误的标志。 当源文档中的页面复制到目标文档中时，如果源文件中的某些对象在此标志为假时损坏，则复制过程将停止，异常 。 示例：dest.Pages.Add(src.Pages); 如果此标志设置为 true，则损坏的对象将被替换为空值。 默认情况下：true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### 也可以看看

* class [Document](../../document)
* 命名空间 [Aspose.Pdf](../../document)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->