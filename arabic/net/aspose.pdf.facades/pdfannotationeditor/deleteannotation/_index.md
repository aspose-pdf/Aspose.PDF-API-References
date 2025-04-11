---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تحذف التعليق مع اسم التعليق المحدد
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## طريقة PdfAnnotationEditor.DeleteAnnotation

تحذف التعليق مع اسم التعليق المحدد.

```csharp
public void DeleteAnnotation(string annotName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| annotName | سلسلة | اسم التعليق |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* الفئة [PdfAnnotationEditor](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)