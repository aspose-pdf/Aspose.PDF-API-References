---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。 从文档中移除打开操作。 当连接多个在启动时使用显式 GoTo 操作的文档时，此操作非常有用。
type: docs
weight: 430
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction 方法

从文档中移除打开操作。 当连接多个在启动时使用显式 'GoTo' 操作的文档时，此操作非常有用。

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

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)