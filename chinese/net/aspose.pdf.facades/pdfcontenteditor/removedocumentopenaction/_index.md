---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 移除文档中的打开操作。当合并多个在启动时使用显式 GoTo 操作的文档时，此操作非常有用。"
type: docs
weight: 430
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

从文档中移除打开操作。当合并多个在启动时使用显式 'GoTo' 操作的文档时，此操作很有用。

```csharp
public void RemoveDocumentOpenAction()
```

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


