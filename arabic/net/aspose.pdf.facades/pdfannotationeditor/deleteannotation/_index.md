---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تحذف التعليق التوضيحي بالاسم المحدد."
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

يحذف التعليق التوضيحي بالاسم المحدد.

```csharp
public void DeleteAnnotation(string annotName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotName | String | اسم التعليق التوضيحي |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


