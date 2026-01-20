---
title: Aspose::Pdf::Vector::SvgExtractor class
linktitle: SvgExtractor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::SvgExtractor class. Represents a class to SVG-images extraction from page in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.vector/svgextractor/
---
## SvgExtractor class


Represents a class to SVG-images extraction from page.

```cpp
class SvgExtractor : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Extract](./extract/)(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>) | Exracts svg image to string from graphic elements represents by [absorber](../) with a predicate filter. |
| [Extract](./extract/)(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>, System::String) | Exracts svg image to file from graphic elements represents by [absorber](../) with a predicate filter. |
| [Extract](./extract/)(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>) | Extracts graphic elements into a SVG string. Options ignored - grouping, extracting from rectangle. |
| [Extract](./extract/)(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>, System::String) | Extracts graphic elements into a single SVG file. Options ignored - grouping, extracting from rectangle. |
| [Extract](./extract/)(System::SharedPtr\<Page\>) | Extracts Svg images from a page to strings. |
| [Extract](./extract/)(System::SharedPtr\<Page\>, System::String) | Extracts Svg images from a page to files. |
| [SvgExtractor](./svgextractor/)() | Represents a class to extract SVG images from a page. |
| [SvgExtractor](./svgextractor/)(System::SharedPtr\<SvgExtractionOptions\>) | Represents a class to extract SVG images from a page. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
