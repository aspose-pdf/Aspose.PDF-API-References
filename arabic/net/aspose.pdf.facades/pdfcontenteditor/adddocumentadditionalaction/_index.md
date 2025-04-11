---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تضيف إجراءً إضافيًا لحدث الوثيقة
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## طريقة PdfContentEditor.AddDocumentAdditionalAction

تضيف إجراءً إضافيًا لحدث الوثيقة.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| eventType | سلسلة | أنواع أحداث الوثيقة. |
| code | سلسلة | كود JavaScript. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)