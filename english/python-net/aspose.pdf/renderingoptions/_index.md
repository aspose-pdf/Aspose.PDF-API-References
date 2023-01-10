---
title: RenderingOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents rendering options.
type: docs
weight: 1330
url: /python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

Represents rendering options.

The RenderingOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|RenderingOptions()|Initializes a new instance of the RenderingOptions class|
## Properties
| Name | Description |
| :- | :- |
|barcode_optimization|Gets or sets barcode optimization mode.|
|optimize_dimensions|Gets or sets optimize dimensions mode.|
|system_fonts_native_rendering|Gets or sets a mode where system fonts are rendered natively.|
|use_new_imaging_engine|Gets or sets a flag determines whether new imaging engine is used or not.|
|width_extra_units|Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.|
|height_extra_units|Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.|
|convert_fonts_to_unicode_ttf|Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility <br/>             reasons and to optimize font usage, cause every new TTF font will have not all the symbols <br/>             from source font, but only symbols which are used in text.|
|use_font_hinting|Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display <br/>            of an outline font. In some cases turning this flag on may solve problems with text legibility. <br/>            At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.|
|scale_images_to_fit_page_width|Gets or sets a values used to scale all images on the page to fit page's width.|
|interpolation_high_quality|Gets or sets hiqh quality mode for interpolation.|
|max_fonts_cache_size|Maximum count of fonts in fonts cache. Default value is 10.|
|max_symbols_cache_size|Maximum count of symbols in symbol cache. Default value is 100.|
|default_font_name|Gets/sets the default name of font used to substitute of missing fonts.|
|ignore_resource_font_errors|Gets or sets indication that errors related to absence of font will be ignored.<br/>            true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing.<br/>            false by default|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

