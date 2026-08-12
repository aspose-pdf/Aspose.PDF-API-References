---
title: "Aspose::Pdf::Facades::PdfConverter::MergeImages metod"
linktitle: "MergeImages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfConverter::MergeImages metod. Slår samman en lista med bildströmmar till en enda bildström. Png/jpg/tiff‑utdataformat stöds, och om ett icke‑stött format används kodas utdataströmmen som Jpeg som standard i C++."
type: docs
weight: 2800
url: /sv/cpp/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter::MergeImages method


Sammanfogar en lista med bildströmmar till en bildström. Png/jpg/tiff-utdataformat stöds, vid användning av ett icke‑stött format kodas utströmmen som Jpeg som standard.

```cpp
static System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImages(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> &inputImagesStreams, Aspose::Pdf::Drawing::ImageFormat outputImageFormat, ImageMergeMode mergeMode, System::Nullable<int32_t> horizontal, System::Nullable<int32_t> vertical)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputImagesStreams | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\& | Listan med bildströmmar att slå samman. |
| outputImageFormat | Aspose::Pdf::Drawing::ImageFormat | [Image](../../../aspose.pdf/image/) utdataformat för den sammanslagna strömmen. |
| mergeMode | ImageMergeMode | Sammanslagningsläge. Används för Png/Jpg-format. |
| horizontal | System::Nullable\<int32_t\> | Horisontellt förhållande för att sätta canvasbredd för utdata bildström. Används endast för Png/Jpg-format med [ImageMergeMode.Center](../../imagemergemode/). |
| vertical | System::Nullable\<int32_t\> | Vertikalt förhållande för att sätta canvashöjd för utdata bildström. Används endast för Png/Jpg-format med [ImageMergeMode.Center](../../imagemergemode/). |

### ReturnValue

[Image](../../../aspose.pdf/image/) stream encoded as output image format.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [List](../../../system.collections.generic/list/)
* Enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* Enum [ImageMergeMode](../../imagemergemode/)
* Class [Nullable](../../../system/nullable/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
