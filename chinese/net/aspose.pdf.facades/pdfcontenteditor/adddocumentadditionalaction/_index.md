---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。为文档事件添加额外操作"
type: docs
weight: 60
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

为文档事件添加额外操作。

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eventType | String | 文档事件类型。 |
| `code` | String | JavaScript 代码。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


