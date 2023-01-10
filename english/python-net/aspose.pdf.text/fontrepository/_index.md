---
title: FontRepository
second_title: Aspose.PDF for Python via .NET API Reference
description: Performs font search. Searches in system installed fonts and standard Pdf fonts.<br/>             Also provides functionality to open custom fonts.
type: docs
weight: 130
url: /python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Performs font search. Searches in system installed fonts and standard Pdf fonts.<br/>             Also provides functionality to open custom fonts.

The FontRepository type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FontRepository()|Initializes a new instance of the FontRepository class|
## Properties
| Name | Description |
| :- | :- |
|substitutions|Gets font substitution strategies collection.|
|sources|Gets font sources collection.|
## Methods
| Name | Description |
| :- | :- |
|find_font(font_name)|Searches and returns font with specified font name.|
|find_font(font_name, ignore_case)|Searches and returns font with specified font name ignoring or honoring case sensitivity.|
|find_font(font_family_name, stl)|Searches and returns font with specified font name and font style.|
|find_font(font_family_name, stl, ignore_case)|Searches and returns font with specified font name and font style <br/>             ignoring or honoring case sensitivity.|
|open_font(font_stream, font_type)|Opens font with specified font stream.|
|open_font(font_file_path)|Opens font with specified font file path.|
|open_font(font_file_path, metrics_file_path)|Opens font with specified font file path.|
|load_fonts()|Loads system installed fonts and standard Pdf fonts. This method was designed to speed up font loading process.<br/>            By default fonts are loaded on first request for any font. Use of this method loads system and standard Pdf fonts<br/>            immediately before any Pdf document was open.|
|reload_fonts()|Reloads all fonts specified by property [sources](/pdf/python-net/aspose.pdf.text/fontrepository/)|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

