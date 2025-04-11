---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. تتحقق مما إذا كانت هناك المزيد من الصور المتاحة في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## طريقة PdfExtractor.HasNextImage

تتحقق مما إذا كانت هناك المزيد من الصور المتاحة في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool HasNextImage()
```

### قيمة الإرجاع

صحيح إذا كانت هناك المزيد من الصور المتاحة

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