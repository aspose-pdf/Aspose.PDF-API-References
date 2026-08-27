---
title: "PdfExtractor.HasNextImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. تتحقق مما إذا كانت هناك صور إضافية يمكن الوصول إليها في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة"
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

يتحقق مما إذا كانت هناك صور إضافية يمكن الوصول إليها في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool HasNextImage()
```

### قيمة الإرجاع

صحيح إذا كانت هناك صور إضافية يمكن الوصول إليها

## أمثلة

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


