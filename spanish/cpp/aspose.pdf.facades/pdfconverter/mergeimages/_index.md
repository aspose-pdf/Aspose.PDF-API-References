---
title: "Aspose::Pdf::Facades::PdfConverter::MergeImages method"
linktitle: "MergeImages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfConverter::MergeImages method. Fusiona una lista de flujos de imagen en un único flujo de imagen. Se admiten los formatos de salida Png/jpg/tiff; en caso de usar un formato no compatible, el flujo de salida se codifica como Jpeg por defecto en C++."
type: docs
weight: 2800
url: /es/cpp/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter::MergeImages method


Fusiona una lista de flujos de imágenes en un solo flujo de imágenes. Se admiten los formatos de salida Png/jpg/tiff; en caso de usar un formato no compatible, el flujo de salida se codifica como Jpeg por defecto.

```cpp
static System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImages(const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> &inputImagesStreams, Aspose::Pdf::Drawing::ImageFormat outputImageFormat, ImageMergeMode mergeMode, System::Nullable<int32_t> horizontal, System::Nullable<int32_t> vertical)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputImagesStreams | const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\& | La lista de flujos de imágenes para combinar. |
| outputImageFormat | Aspose::Pdf::Drawing::ImageFormat | [Image](../../../aspose.pdf/image/) formato de salida para el flujo combinado. |
| mergeMode | ImageMergeMode | Modo de combinación. Usado para formatos Png/Jpg. |
| horizontal | System::Nullable\<int32_t\> | Proporción horizontal para establecer el ancho del lienzo del flujo de imagen de salida. Usado solo para formatos Png/Jpg con [ImageMergeMode.Center](../../imagemergemode/). |
| vertical | System::Nullable\<int32_t\> | Proporción vertical para establecer la altura del lienzo del flujo de imagen de salida. Usado solo para formatos Png/Jpg con [ImageMergeMode.Center](../../imagemergemode/). |

### ReturnValue

[Image](../../../aspose.pdf/image/) stream encoded as output image format.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [List](../../../system.collections.generic/list/)
* Enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* Enum [ImageMergeMode](../../imagemergemode/)
* Class [Nullable](../../../system/nullable/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
