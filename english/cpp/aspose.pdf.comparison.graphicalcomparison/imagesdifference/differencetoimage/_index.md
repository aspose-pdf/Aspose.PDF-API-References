---
title: Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage method
linktitle: DifferenceToImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage method. Converts the difference array to a bitmap image using the specified colors in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.comparison.graphicalcomparison/imagesdifference/differencetoimage/
---
## ImagesDifference::DifferenceToImage method


Converts the difference array to a bitmap image using the specified colors.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::Drawing::Bitmap> Aspose::Pdf::Comparison::GraphicalComparison::ImagesDifference::DifferenceToImage(System::SharedPtr<Color> color, System::SharedPtr<Color> backgroundColor)
```


| Parameter | Type | Description |
| --- | --- | --- |
| color | System::SharedPtr\<Color\> | The color for non-zero differences. |
| backgroundColor | System::SharedPtr\<Color\> | The background color for zero differences. |

### ReturnValue

A bitmap image representing the difference array.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>color</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The color for non-zero differences.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>backgroundColor</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The background color for zero differences.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Color](../../../aspose.pdf/color/)
* Class [ImagesDifference](../)
* Namespace [Aspose::Pdf::Comparison::GraphicalComparison](../../)
* Library [Aspose.PDF for C++](../../../)
