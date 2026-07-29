---
title: "Document.IgnoreCorruptedObjects"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 属性。获取或设置在源文件中忽略错误的标志。当从源文档复制页面到目标文档时，如果此标志为 false，且源文件中的某些对象损坏，则复制过程会因异常而停止。例如 dest.Pages.Addsrc.Pages。如果此标志设置为 true，则损坏的对象将被替换为空值。默认值为 true。"
type: docs
weight: 290
url: /zh/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

获取或设置在源文件中忽略错误的标志。当将源文档的页面复制到目标文档时，如果源文件中的某些对象损坏且此标志为 false，则复制过程会因异常而停止。例如：dest.Pages.Add(src.Pages); 如果此标志设置为 true，则损坏的对象将被替换为空值。默认值：true。

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### 另请参见

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


