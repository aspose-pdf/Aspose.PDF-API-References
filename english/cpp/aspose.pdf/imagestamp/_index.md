---
title: Aspose::Pdf::ImageStamp class
linktitle: ImageStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ImageStamp class. Represents a graphic stamp in C++.'
type: docs
weight: 8300
url: /cpp/aspose.pdf/imagestamp/
---
## ImageStamp class


Represents a graphic stamp.

```cpp
class ImageStamp : public Aspose::Pdf::Stamp
```

## Methods

| Method | Description |
| --- | --- |
| [get_AlternativeText](./get_alternativetext/)() const | Gets Alternative [Text](../../aspose.pdf.text/) for image stamp. |
| [get_Height](./get_height/)() override | Gets image height. Setting this image allows to scale image vertically. |
| [get_Image](./get_image/)() const | Gets image stream used for stamping. |
| [get_Quality](./get_quality/)() const | Gets quality of image stamp in percent. Valid values are 0..100%. |
| [get_Width](./get_width/)() override | Gets image width. Setting this property allos to scal image horizontally. |
| [get_XIndent](./get_xindent/)() override | Gets and sets horizontal stamp coordinate, starting from the left. |
| [get_YIndent](./get_yindent/)() override | Gets and sets vertical stamp coordinate, starting from the bottom. |
| [ImageStamp](./imagestamp/)(System::SharedPtr\<System::IO::Stream\>) | Initializes a new instance of the [ImageStamp](./) class. |
| [ImageStamp](./imagestamp/)(System::String) | Creates image stamp by image in the specified file. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Adds graphic stamp on the page. |
| [set_AlternativeText](./set_alternativetext/)(System::String) | Sets Alternative [Text](../../aspose.pdf.text/) for image stamp. |
| [set_Height](./set_height/)(double) override | Sets image height. Setting this image allows to scale image vertically. |
| [set_Quality](./set_quality/)(int32_t) | Sets quality of image stamp in percent. Valid values are 0..100%. |
| [set_Width](./set_width/)(double) override | Sets image width. Setting this property allos to scal image horizontally. |
| [set_XIndent](./set_xindent/)(double) override | Gets and sets horizontal stamp coordinate, starting from the left. |
| [set_YIndent](./set_yindent/)(double) override | Gets and sets vertical stamp coordinate, starting from the bottom. |
## See Also

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
