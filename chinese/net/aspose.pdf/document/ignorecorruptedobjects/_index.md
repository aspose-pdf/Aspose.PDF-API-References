---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: 文档属性。获取或设置忽略源文件中错误的标志。当源文档中的页面复制到目标文档时，如果源文件中的某些对象损坏且此标志为 false，则复制过程会因异常而停止。如果此标志设置为 true，则损坏的对象将被替换为空值。默认值：true
type: docs
weight: 270
url: /zh/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects 属性

获取或设置忽略源文件中错误的标志。当源文档中的页面复制到目标文档时，如果源文件中的某些对象损坏且此标志为 false，则复制过程会因异常而停止。示例：dest.Pages.Add(src.Pages); 如果此标志设置为 true，则损坏的对象将被替换为空值。默认值：true。

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### 另请参阅

* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)