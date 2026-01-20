---
title: Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth method
linktitle: set_MinStrokeWidth
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth method. Sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5 in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.vector/svgextractionoptions/set_minstrokewidth/
---
## SvgExtractionOptions::set_MinStrokeWidth method


Sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5.

```cpp
void Aspose::Pdf::Vector::SvgExtractionOptions::set_MinStrokeWidth(double value)
```

## Remarks


The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG. 
## See Also

* Class [SvgExtractionOptions](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
