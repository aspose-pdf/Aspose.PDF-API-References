---
title: "PdfExtractor.ExtractImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Извлекать изображения из PDF‑файла"
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

Извлекает изображения из PDF-файла.

```csharp
public void ExtractImage()
```

## Примеры

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

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


