---
title: "PdfPageEditor.GetPageSize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfPageEditor. تُرجع حجم الصفحة للصفحة المحددة"
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

يعيد حجم الصفحة للصفحة المحددة.

```csharp
public PageSize GetPageSize(int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | فهرس الصفحة. صفحات المستند مرقمة بدءًا من 1. |

### قيمة الإرجاع

النتيجة هي كائن من نوع PageSize. استخدم خصائص Width و Height للكائن المرتجع للحصول على عرض الصفحة وارتفاعها.

## أمثلة

المثال التالي يوضح استخدام طريقة GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


