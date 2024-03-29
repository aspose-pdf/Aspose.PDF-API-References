---
title: HasNextImage
second_title: Aspose.PDF для справочника API .NET
description: Проверяет доступны ли дополнительные изображения в документе PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Проверяет, доступны ли дополнительные изображения в документе PDF. Примечание. Перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool HasNextImage()
```

### Возвращаемое значение

Верно, если доступно больше изображений

### Примеры

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

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
