---
title: Aspose::Pdf::Facades::PdfConverter::MergeImages method
linktitle: MergeImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfConverter::MergeImages method. Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default in C++.'
type: docs
weight: 2800
url: /cpp/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter::MergeImages method


Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default.

```cpp
static System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImages(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> inputImagesStreams, Aspose::Pdf::Drawing::ImageFormat outputImageFormat, ImageMergeMode mergeMode, System::Nullable<int32_t> horizontal, System::Nullable<int32_t> vertical)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputImagesStreams | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\> | The list of image streams to merge. |
| outputImageFormat | Aspose::Pdf::Drawing::ImageFormat | [Image](../../../aspose.pdf/image/) output format for merged stream. |
| mergeMode | ImageMergeMode | Merge mode. Used for Png/Jpg formats. |
| horizontal | System::Nullable\<int32_t\> | Horizontal ratio to set canvas width for output image stream. Used for Png/Jpg formats with [ImageMergeMode.Center](../../imagemergemode/) only. |
| vertical | System::Nullable\<int32_t\> | Vertical ratio to set canvas height for output image stream. Used for Png/Jpg formats with [ImageMergeMode.Center](../../imagemergemode/) only. |

### ReturnValue

[Image](../../../aspose.pdf/image/) stream encoded as output image format.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [List](../../../system.collections.generic/list/)
* Enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* Enum [ImageMergeMode](../../imagemergemode/)
* Class [Nullable](../../../system/nullable/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
