---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تعيد حجم الصندوق المحدد في الوثيقة
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## طريقة PdfPageEditor.GetPageBoxSize

تعيد حجم الصندوق المحدد في الوثيقة.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| page | Int32 | فهرس الصفحة. يتم ترقيم صفحات الوثيقة من 1. |
| pageBoxName | String | اسم نوع الصندوق. القيم الصالحة هي: "art"، "bleed"، "crop"، "media"، "trim". |

### قيمة الإرجاع

مستطيل يحتوي على الصندوق المطلوب.

## أمثلة

المثال التالي يوضح كيفية الحصول على صندوق الوسائط للصفحة الأولى:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)