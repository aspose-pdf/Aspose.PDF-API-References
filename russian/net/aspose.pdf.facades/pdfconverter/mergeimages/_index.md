---
title: "PdfConverter.MergeImages"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfConverter. Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; в случае использования неподдерживаемого формата поток вывода кодируется как Jpeg по умолчанию"
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; при использовании неподдерживаемого формата поток вывода по умолчанию кодируется как Jpeg.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | List`1 | Список потоков изображений для объединения. |
| outputImageFormat | ImageFormat | Формат вывода изображения для объединённого потока. |
| mergeMode | ImageMergeMode | Режим объединения. Используется для форматов Png/Jpg. |
| horizontal | Nullable`1 | Горизонтальное соотношение для установки ширины холста выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center только. |
| vertical | Nullable`1 | Вертикальное соотношение для установки высоты холста выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center только. |

### Возвращаемое значение

Поток изображения, закодированный в формате вывода изображения.

### См. также

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


