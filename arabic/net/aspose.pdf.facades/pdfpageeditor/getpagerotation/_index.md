---
title: "PdfPageEditor.GetPageRotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfPageEditor. تُعيد دوران الصفحة المحددة"
type: docs
weight: 140
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

يعيد دوران الصفحة المحددة.

```csharp
public int GetPageRotation(int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | فهرس الصفحة. صفحات المستند مرقمة بدءًا من 1. |

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


