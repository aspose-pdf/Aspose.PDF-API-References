---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfConverter. Объединяет список потоков изображений в один поток изображений. Поддерживаются форматы вывода Png/jpg/tiff в случае использования неподдерживаемого формата, поток вывода кодируется как Jpeg по умолчанию
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Метод PdfConverter.MergeImages

Объединяет список потоков изображений в один поток изображений. Поддерживаются форматы вывода Png/jpg/tiff, в случае использования неподдерживаемого формата, поток вывода кодируется как Jpeg по умолчанию.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | List`1 | Список потоков изображений для объединения. |
| outputImageFormat | ImageFormat | Формат изображения для объединенного потока. |
| mergeMode | ImageMergeMode | Режим объединения. Используется для форматов Png/Jpg. |
| horizontal | Nullable`1 | Горизонтальное соотношение для установки ширины холста для выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center. |
| vertical | Nullable`1 | Вертикальное соотношение для установки высоты холста для выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center. |

### Возвращаемое значение

Поток изображения, закодированный в формате выходного изображения.

### См. также

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)