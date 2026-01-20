---
title: Aspose::Pdf::Vector::SvgExtractionOptions class
linktitle: SvgExtractionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::SvgExtractionOptions class. Represents an options class for extracting vector graphics from the pdf document page in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class


Represents an options class for extracting vector graphics from the pdf document page.

```cpp
class SvgExtractionOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AutoGrouping](./get_autogrouping/)() const | Gets and sets the option to automatically group subpaths into images. This option excludes the [GroupStrength](../) option. |
| [get_ExtractEverySubPathToSvg](./get_extracteverysubpathtosvg/)() const | Gets and sets opttion to extracts every subpath from a PDF document to separate SVG images. |
| [get_ExtractionAreaBound](./get_extractionareabound/)() const | Gets and sets the bounding rectangle that defines the extraction area for SVG extraction. |
| [get_GroupStrength](./get_groupstrength/)() const | Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the [ExtractEverySubPathToSvg](../) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when [AutoGrouping](../) is false. The default value is **0.8**. |
| [get_MinStrokeWidth](./get_minstrokewidth/)() const | Gets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. |
| [get_StrictExtractionAreaBoundCheck](./get_strictextractionareaboundcheck/)() const | Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in [ExtractionAreaBound](../). If set to false, then subpaths that are not completely included in [ExtractionAreaBound](../) will be extracted. The default value is **True**. |
| [get_UnpackPageContentXForm](./get_unpackpagecontentxform/)() const | Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked. |
| [get_UnpackXFormPredicate](./get_unpackxformpredicate/)() const | Gets and sets option to unpack only the [XForm](../../aspose.pdf/xform/) corresponding to the specified predicate. |
| [set_AutoGrouping](./set_autogrouping/)(bool) | Gets and sets the option to automatically group subpaths into images. This option excludes the [GroupStrength](../) option. |
| [set_ExtractEverySubPathToSvg](./set_extracteverysubpathtosvg/)(bool) | Gets and sets opttion to extracts every subpath from a PDF document to separate SVG images. |
| [set_ExtractionAreaBound](./set_extractionareabound/)(System::SharedPtr\<Rectangle\>) | Gets and sets the bounding rectangle that defines the extraction area for SVG extraction. |
| [set_GroupStrength](./set_groupstrength/)(double) | Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the [ExtractEverySubPathToSvg](../) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when [AutoGrouping](../) is false. The default value is **0.8**. |
| [set_MinStrokeWidth](./set_minstrokewidth/)(double) | Sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. |
| [set_StrictExtractionAreaBoundCheck](./set_strictextractionareaboundcheck/)(bool) | Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in [ExtractionAreaBound](../). If set to false, then subpaths that are not completely included in [ExtractionAreaBound](../) will be extracted. The default value is **True**. |
| [set_UnpackPageContentXForm](./set_unpackpagecontentxform/)(bool) | Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked. |
| [set_UnpackXFormPredicate](./set_unpackxformpredicate/)(System::Predicate\<System::SharedPtr\<XFormPlacement\>\>) | Gets and sets option to unpack only the [XForm](../../aspose.pdf/xform/) corresponding to the specified predicate. |
| [SvgExtractionOptions](./svgextractionoptions/)() | Creates [SvgExtractionOptions](./) class instance. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
