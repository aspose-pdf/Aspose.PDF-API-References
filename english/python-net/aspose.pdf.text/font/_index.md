---
title: Font
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents font object.
type: docs
weight: 100
url: /python-net/aspose.pdf.text/font/
---

## Font class

Represents font object.

The Font type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|font_name|Gets font name of the [Font](/pdf/python-net/aspose.pdf.text/font/) object.|
|decoded_font_name|Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name.<br/>            This name is value of PDF font property "BaseFont" and sometimes this property<br/>            could be represented in hexademical form. If read this name directly it could be represented<br/>            in non-readable form. To get readable form it's necessary to decode font's name by<br/>            rules specifical for this font. <br/>            This property returns decoded font name, so use it for cases when you meet <br/>            with a non-readable [font_name](/pdf/python-net/aspose.pdf.text/font/).<br/>            If property [font_name](/pdf/python-net/aspose.pdf.text/font/) has readable form this property will be the same as <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), so you can use this property for any cases when you need to<br/>            get font name in a readable form.|
|base_font|Gets BaseFont value of PDF font object. Also known as PostScript name of the font.|
|is_embedded|Gets or sets a value that indicates whether the font is embedded.<br/>            Font based on IFont will automatically be subset and embedded|
|is_subset|Gets or sets a value that indicates whether the font is a subset.<br/>             Font based on IFont will automatically be subset and embedded|
|is_accessible|Gets indicating whether the font is present (installed) in the system.|
|font_options|Useful properties to tune Font behaviour|
## Methods
| Name | Description |
| :- | :- |
|get_last_font_embedding_error()|An objective of this method - to return description of error if an attempt<br/>            to embed font was failed. If there are no error cases it returns empty string.|
|save(stream)|Saves the font into the stream.<br/>            Note that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only.<br/>            The font file is not intended to be used outside the original document context.|
|measure_string(str, font_size)|Measures the string.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

