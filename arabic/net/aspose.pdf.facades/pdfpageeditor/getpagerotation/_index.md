---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تعيد دوران الصفحة المحددة
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## طريقة PdfPageEditor.GetPageRotation

تعيد دوران الصفحة المحددة.

```csharp
public int GetPageRotation(int page)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| page | Int32 | فهرس الصفحة. يتم ترقيم صفحات الوثيقة من 1. |

### قيمة الإرجاع

دوران الصفحة بالدرجات.

## أمثلة

المثال التالي يوضح كيفية الحصول على دوران الصفحة:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)