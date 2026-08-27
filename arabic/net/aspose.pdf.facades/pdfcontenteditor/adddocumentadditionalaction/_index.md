---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تضيف إجراءً إضافيًا لحدث المستند"
type: docs
weight: 60
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

يضيف إجراءً إضافيًا لحدث المستند.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| eventType | String | أنواع أحداث المستند. |
| الرمز | String | كود JavaScript. |

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


