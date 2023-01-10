---
title: ImageCompressionOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Class contains set  options for image compression.
type: docs
weight: 10
url: /python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Class contains set  options for image compression.

The ImageCompressionOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ImageCompressionOptions()|Initializes a new instance of the ImageCompressionOptions class|
## Properties
| Name | Description |
| :- | :- |
|compress_images|If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.|
|resize_images|If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.|
|image_quality|Specifies level of image compression when CompressIamges flag is used.|
|max_resolution|Specifies maximum resolution of images. If image has higher resolition it will be scaled|
|version|Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by  faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".|
|encoding|Gets or sets encoding used to store images.|

### See Also

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

