---
title: PdfContentEditor.DeleteAttachments
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。删除 PDF 文档中的所有附件
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## PdfContentEditor.DeleteAttachments 方法

删除 PDF 文档中的所有附件。

```csharp
public void DeleteAttachments()
```

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)