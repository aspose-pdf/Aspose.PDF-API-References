---
title: PdfContentEditor.DeleteAttachments
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تحذف جميع المرفقات في مستند PDF
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/deleteattachments/
---
## PdfContentEditor.DeleteAttachments method

تحذف جميع المرفقات في مستند PDF.

```csharp
public void DeleteAttachments()
```

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteAttachments();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)