---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfExtractor. Извлечение изображений из PDF файла
type: docs
weight: 120
url: /ru/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Метод PdfExtractor.ExtractImage

Извлечение изображений из PDF файла.

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

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)