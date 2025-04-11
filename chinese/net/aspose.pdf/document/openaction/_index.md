---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: 文档属性。获取或设置在文档打开时执行的操作
type: docs
weight: 390
url: /zh/net/aspose.pdf/document/openaction/
---
## Document.OpenAction 属性

获取或设置在文档打开时执行的操作。

```csharp
public IAppointment OpenAction { get; set; }
```

## 示例

示例演示如何获取 CenterWindow 标志：

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### 另请参阅

* 接口 [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* 类 [Document](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)