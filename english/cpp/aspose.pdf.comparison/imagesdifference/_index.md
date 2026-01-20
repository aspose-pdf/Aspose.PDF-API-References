---
title: Aspose::Pdf::Comparison::ImagesDifference class
linktitle: ImagesDifference
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::ImagesDifference class. Represents the result class of comparing two PDF pages in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class


Represents the result class of comparing two PDF pages.

```cpp
class ImagesDifference : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [DifferenceToImage](./differencetoimage/)(System::SharedPtr\<Color\>, System::SharedPtr\<Color\>) | Converts the difference array to a bitmap image using the specified colors. |
| [Dispose](./dispose/)() override | Performs any necessary clean up operations before the object is destroyed. |
| [get_Difference](./get_difference/)() const | Gets the difference array. This array is similar to the original image data array obtained as a result of the LockBits method. |
| [get_Height](./get_height/)() const | The height of difference. |
| [get_SourceImage](./get_sourceimage/)() const | Gets the image of first compared page. The image has a pixel format is 24bpp. |
| [get_Stride](./get_stride/)() const | The stride of difference image data. |
| [GetDestinationImage](./getdestinationimage/)() | Returns a new bitmap representing the destination image by applying the difference array to the source image. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
