---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。为文档事件添加额外操作
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction 方法

为文档事件添加额外操作。

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | 字符串 | 文档事件类型。 |
| code | 字符串 | JavaScript 代码。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)