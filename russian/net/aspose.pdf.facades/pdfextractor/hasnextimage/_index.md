---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfExtractor. Проверяет, доступны ли дополнительные изображения в PDF-документе. Обратите внимание, что метод ExtractImage должен быть вызван перед использованием этого метода
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Метод PdfExtractor.HasNextImage

Проверяет, доступны ли дополнительные изображения в PDF-документе. Обратите внимание: метод ExtractImage должен быть вызван перед использованием этого метода.

```csharp
public bool HasNextImage()
```

### Возвращаемое значение

True, если доступны дополнительные изображения

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