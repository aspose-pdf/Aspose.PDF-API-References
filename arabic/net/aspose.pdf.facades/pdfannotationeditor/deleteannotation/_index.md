---
title: DeleteAnnotation
second_title: Aspose.PDF لمرجع .NET API
description: حذف التعليق التوضيحي باسم التعليق التوضيحي المحدد.
type: docs
weight: 20
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

حذف التعليق التوضيحي باسم التعليق التوضيحي المحدد.

```csharp
public void DeleteAnnotation(string annotName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotName | String | اسم التعليق التوضيحي |

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->