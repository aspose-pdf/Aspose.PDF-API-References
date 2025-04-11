---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تزيل إجراء الفتح من الوثيقة. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء 'GoTo' صريح عند بدء التشغيل
type: docs
weight: 430
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

تزيل إجراء الفتح من الوثيقة. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء 'GoTo' صريح عند بدء التشغيل.

```csharp
public void RemoveDocumentOpenAction()
```

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)