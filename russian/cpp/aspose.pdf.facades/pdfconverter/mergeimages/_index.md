---
title: "Метод Aspose::Pdf::Facades::PdfConverter::MergeImages"
linktitle: "MergeImages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfConverter::MergeImages. Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; в случае использования неподдерживаемого формата поток вывода кодируется как Jpeg по умолчанию в C++."
type: docs
weight: 2800
url: /ru/cpp/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter::MergeImages method


Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; при использовании неподдерживаемого формата поток вывода по умолчанию кодируется как JPEG.

```cpp
static System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImages(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> &inputImagesStreams, Aspose::Pdf::Drawing::ImageFormat outputImageFormat, ImageMergeMode mergeMode, System::Nullable<int32_t> horizontal, System::Nullable<int32_t> vertical)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\& | Список потоков изображений для объединения. |
| outputImageFormat | Aspose::Pdf::Drawing::ImageFormat | Формат вывода [Image](../../../aspose.pdf/image/) для объединённого потока. |
| mergeMode | ImageMergeMode | Режим объединения. Используется для форматов Png/Jpg. |
| horizontal | System::Nullable\<int32_t\> | Горизонтальное соотношение для установки ширины холста выходного потока изображения. Используется только для форматов Png/Jpg с [ImageMergeMode.Center](../../imagemergemode/). |
| vertical | System::Nullable\<int32_t\> | Вертикальное соотношение для установки высоты холста выходного потока изображения. Используется только для форматов Png/Jpg с [ImageMergeMode.Center](../../imagemergemode/). |

### ReturnValue

[Image](../../../aspose.pdf/image/) stream encoded as output image format.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [List](../../../system.collections.generic/list/)
* Enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* Enum [ImageMergeMode](../../imagemergemode/)
* Class [Nullable](../../../system/nullable/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
