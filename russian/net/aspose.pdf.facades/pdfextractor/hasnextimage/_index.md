---
title: "PdfExtractor.HasNextImage"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Проверяет, доступны ли дополнительные изображения в PDF‑документе. Примечание: ExtractImage должен быть вызван до использования этого метода"
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Проверяет, доступны ли дополнительные изображения в PDF-документе. Примечание: перед использованием этого метода необходимо вызвать ExtractImage.

```csharp
public bool HasNextImage()
```

### Возвращаемое значение

Истина, если доступны дополнительные изображения

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


