---
title: TextAbsorber
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents an absorber object of a text.<br/>            Performs text extraction and provides access to the result via [text](/pdf/python-net/aspose.pdf.text/textabsorber/) object.
type: docs
weight: 320
url: /python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Represents an absorber object of a text.<br/>            Performs text extraction and provides access to the result via [text](/pdf/python-net/aspose.pdf.text/textabsorber/) object.

The TextAbsorber type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|TextAbsorber()|Initializes a new instance of the [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/).|
|TextAbsorber(extraction_options)|Initializes a new instance of the TextAbsorber class|
|TextAbsorber(extraction_options, text_search_options)|Initializes a new instance of the TextAbsorber class|
|TextAbsorber(text_search_options)|Initializes a new instance of the TextAbsorber class|
## Properties
| Name | Description |
| :- | :- |
|text|Gets extracted text that the [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extracts on the PDF document or page.|
|has_errors|Value indicates whether errors were found during text extraction.<br/>            Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.|
|errors|List of [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) objects. It contain information about errors were found during text extraction.<br/>            Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance.|
|extraction_options|Gets or sets text extraction options.|
|text_search_options|Gets or sets text search options.|
## Methods
| Name | Description |
| :- | :- |
|visit(page)|Extracts text on the specified page|
|visit(form)|Extracts text on the specified XForm.|
|visit(pdf)|Extracts text on the specified document|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

