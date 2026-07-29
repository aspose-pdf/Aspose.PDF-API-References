---
title: "Document.Actions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 属性。获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。"
type: docs
weight: 30
url: /zh/net/aspose.pdf/document/actions/
---
## Document.Actions property

获取文档操作。此属性是 DocumentActions 类的实例，允许获取/设置 BeforClosing、BeforSaving 等操作。

```csharp
public DocumentActionCollection Actions { get; }
```

## 示例

此示例演示如何获取文档的打开后操作：

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### 另请参见

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


