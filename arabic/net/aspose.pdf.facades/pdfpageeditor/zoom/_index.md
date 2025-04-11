---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfPageEditor. الحصول على معامل التكبير أو تعيينه. القيمة 1.0 تتوافق مع 100. القيمة الافتراضية هي 1.0. المثال التالي يوضح كيفية تغيير تكبير صفحات الوثيقة
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## خاصية PdfPageEditor.Zoom

الحصول على معامل التكبير أو تعيينه. القيمة 1.0 تتوافق مع 100%. القيمة الافتراضية هي 1.0. المثال التالي يوضح كيفية تغيير تكبير صفحات الوثيقة.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)