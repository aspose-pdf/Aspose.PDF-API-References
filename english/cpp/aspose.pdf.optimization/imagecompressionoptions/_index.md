---
title: Aspose::Pdf::Optimization::ImageCompressionOptions class
linktitle: ImageCompressionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Optimization::ImageCompressionOptions class. Class contains set options for image compression in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class


Class contains set options for image compression.

```cpp
class ImageCompressionOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CompressImages](./get_compressimages/)() const | If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property. |
| [get_Encoding](./get_encoding/)() const | Gets encoding used to store images. |
| [get_ImageQuality](./get_imagequality/)() const | Specifies level of image compression when CompressImages flag is used. |
| [get_MaxResolution](./get_maxresolution/)() const | Specifies maximum resolution of images. If image has higher resolution it will be scaled. |
| [get_ResizeImages](./get_resizeimages/)() const | If this flag set to true and CompressImages is true images will be resized if image resolution is greater then specified MaxResolution parameter. |
| [get_Version](./get_version/)() const | Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard". |
| [ImageCompressionOptions](./imagecompressionoptions/)() |  |
| [set_CompressImages](./set_compressimages/)(bool) | If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property. |
| [set_Encoding](./set_encoding/)(ImageEncoding) | Sets encoding used to store images. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Specifies level of image compression when CompressImages flag is used. |
| [set_MaxResolution](./set_maxresolution/)(int32_t) | Specifies maximum resolution of images. If image has higher resolution it will be scaled. |
| [set_ResizeImages](./set_resizeimages/)(bool) | If this flag set to true and CompressImages is true images will be resized if image resolution is greater then specified MaxResolution parameter. |
| [set_Version](./set_version/)(ImageCompressionVersion) | Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard". |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
