---
title: Aspose::Pdf::RenderingOptions class
linktitle: RenderingOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::RenderingOptions class. Represents rendering options in C++.'
type: docs
weight: 16600
url: /cpp/aspose.pdf/renderingoptions/
---
## RenderingOptions class


Represents rendering options.

```cpp
class RenderingOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AnalyzeFonts](./get_analyzefonts/)() const | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: |
| [get_BarcodeOptimization](./get_barcodeoptimization/)() const | Gets barcode optimization mode. |
| [get_ConvertFontsToUnicodeTTF](./get_convertfontstounicodettf/)() const | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Gets/sets the default name of font used to substitute of missing fonts. |
| [get_HeightExtraUnits](./get_heightextraunits/)() const | Gets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Gets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. [Text](../../aspose.pdf.text/) segments that refer to incorrect resources will be skipped during processing. false by default. |
| [get_InterpolationHighQuality](./get_interpolationhighquality/)() const | Gets hiqh quality mode for interpolation. |
| [get_MaxFontsCacheSize](./get_maxfontscachesize/)() const | Maximum count of fonts in fonts cache. Default value is 10. |
| [get_MaxSymbolsCacheSize](./get_maxsymbolscachesize/)() const | Maximum count of symbols in symbol cache. Default value is 100. |
| [get_OptimizeDimensions](./get_optimizedimensions/)() const | Gets optimize dimensions mode. |
| [get_ScaleImagesToFitPageWidth](./get_scaleimagestofitpagewidth/)() const | Gets a values used to scale all images on the page to fit page's width. |
| [get_SystemFontsNativeRendering](./get_systemfontsnativerendering/)() const | Gets a mode where system fonts are rendered natively. |
| [get_UseFontHinting](./get_usefonthinting/)() const | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Gets a flag determines whether new imaging engine is used or not. |
| [get_WidthExtraUnits](./get_widthextraunits/)() const | Gets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [RenderingOptions](./renderingoptions/)() | Initializes new instance of the [RenderingOptions](./) object. |
| [set_AnalyzeFonts](./set_analyzefonts/)(bool) | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: |
| [set_BarcodeOptimization](./set_barcodeoptimization/)(bool) | Sets barcode optimization mode. |
| [set_ConvertFontsToUnicodeTTF](./set_convertfontstounicodettf/)(bool) | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [set_DefaultFontName](./set_defaultfontname/)(System::String) | Gets/sets the default name of font used to substitute of missing fonts. |
| [set_HeightExtraUnits](./set_heightextraunits/)(float) | Sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. [Text](../../aspose.pdf.text/) segments that refer to incorrect resources will be skipped during processing. false by default. |
| [set_InterpolationHighQuality](./set_interpolationhighquality/)(bool) | Sets hiqh quality mode for interpolation. |
| [set_MaxFontsCacheSize](./set_maxfontscachesize/)(int32_t) | Maximum count of fonts in fonts cache. Default value is 10. |
| [set_MaxSymbolsCacheSize](./set_maxsymbolscachesize/)(int32_t) | Maximum count of symbols in symbol cache. Default value is 100. |
| [set_OptimizeDimensions](./set_optimizedimensions/)(bool) | Sets optimize dimensions mode. |
| [set_ScaleImagesToFitPageWidth](./set_scaleimagestofitpagewidth/)(bool) | Sets a values used to scale all images on the page to fit page's width. |
| [set_SystemFontsNativeRendering](./set_systemfontsnativerendering/)(bool) | Sets a mode where system fonts are rendered natively. |
| [set_UseFontHinting](./set_usefonthinting/)(bool) | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Sets a flag determines whether new imaging engine is used or not. |
| [set_WidthExtraUnits](./set_widthextraunits/)(float) | Sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
