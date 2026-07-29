---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء GoTo صريح عند بدء التشغيل"
type: docs
weight: 430
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

يزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج عدة مستندات تستخدم إجراء 'GoTo' صريح عند بدء التشغيل.

```csharp
public void RemoveDocumentOpenAction()
```

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


