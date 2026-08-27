---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfPageEditor. تُرجع حجم الصندوق المحدد في المستند"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

يعيد حجم الصندوق المحدد في المستند.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | Int32 | فهرس الصفحة. صفحات المستند مرقمة بدءًا من 1. |
| pageBoxName | String | اسم نوع الصندوق. القيم الصالحة هي: "art", "bleed", "crop", "media", "trim". |

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


