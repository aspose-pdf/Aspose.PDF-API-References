---
title: "PdfViewer.Resolution"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfViewer. تحصل أو تعين الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة كان السرعة أبطأ. القيمة الافتراضية هي 150"
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

يحصل أو يعيّن الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150.

```csharp
public int Resolution { get; set; }
```

## ملاحظات

تغيّر هذه الخاصية دقة الصورة في عمليات التحويل من صفحة إلى صورة: عندما يتم تعيين [`PrintAsImage`](../printasimage/) إلى `true`، أو عندما يتم استدعاء طريقة [`DecodePage`](../decodepage/) أو [`DecodeAllPages`](../decodeallpages/). لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) في الفئة [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### انظر أيضًا

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


