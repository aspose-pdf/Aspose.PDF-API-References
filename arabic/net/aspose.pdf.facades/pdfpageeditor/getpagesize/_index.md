---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تعيد حجم الصفحة للصفحة المحددة
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## طريقة PdfPageEditor.GetPageSize

تعيد حجم الصفحة للصفحة المحددة.

```csharp
public PageSize GetPageSize(int page)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| page | Int32 | فهرس الصفحة. يتم ترقيم صفحات الوثيقة من 1. |

### قيمة الإرجاع

النتيجة هي مثيل من PageSize. استخدم خصائص Width و Height للكائن المعاد للحصول على عرض وارتفاع الصفحة.

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