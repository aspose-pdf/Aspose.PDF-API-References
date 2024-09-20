---
title: Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage method
linktitle: DifferenceToImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage method. Converts the difference array to a bitmap image using the specified colors in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.comparison.graphicalcomparison/imagesdifference/differencetoimage/
---
## ImagesDifference::DifferenceToImage method


Converts the difference array to a bitmap image using the specified colors.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage(System::SharedPtr<Color> color, System::SharedPtr<Color> backgroundColor)
```


| Parameter | Type | Description |
| --- | --- | --- |
| color | System::SharedPtr\<Color\> | The color for non-zero differences. |
| backgroundColor | System::SharedPtr\<Color\> | The background color for zero differences. |

### ReturnValue

A bitmap image representing the difference array.

## See Also

* Class [Color](../../../aspose.pdf/color/)
* Class [ImagesDifference](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
