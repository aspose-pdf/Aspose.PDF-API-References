---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfViewer. تحصل أو تضبط الدقة أثناء العرض والطباعة. كلما زادت الدقة، زادت البطء. القيمة الافتراضية هي 150
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfviewer/resolution/
---
## خاصية PdfViewer.Resolution

تحصل أو تضبط الدقة أثناء العرض والطباعة. كلما زادت الدقة، زادت البطء. القيمة الافتراضية هي 150.

```csharp
public int Resolution { get; set; }
```

## ملاحظات

تغير هذه الخاصية دقة الصورة في تدفقات تحويل الصفحة إلى صورة: عندما يتم تعيين [`PrintAsImage`](../printasimage/) إلى `true`، أو عندما يتم استدعاء طريقة [`DecodePage`](../decodepage/) أو [`DecodeAllPages`](../decodeallpages/). لتعيين دقة الطابعة للطباعة المباشرة إلى طابعة، استخدم خاصية [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) في فئة [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### انظر أيضًا

* فئة [PdfViewer](../)
* مساحة الأسماء [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)