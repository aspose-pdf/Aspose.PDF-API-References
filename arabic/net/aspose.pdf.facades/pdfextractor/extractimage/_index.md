---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. استخراج الصور من ملف PDF
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## طريقة PdfExtractor.ExtractImage

استخراج الصور من ملف PDF.

```csharp
public void ExtractImage()
```

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