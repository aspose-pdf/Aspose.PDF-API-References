---
title: PdfFileSanitization
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents sanitization and recovery API.<br/>            Use it if you can't create/open documents in any other way.
type: docs
weight: 290
url: /python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Represents sanitization and recovery API.<br/>            Use it if you can't create/open documents in any other way.

The PdfFileSanitization type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileSanitization()|Initializes a new instance of the PdfFileSanitization class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|log|After file has Saved you can check what was done with file.|
|use_trim_top|Allows to remove data before pdf data.|
|use_trim_bottom|Allows to remove data after pdf data|
|use_rebuild_xref_and_trailer|Allows to generate new xref and trailer for document.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(input_file)|Binds a Pdf file for Sanitize.|
|bind_pdf(input_stream)|Binds a Pdf stream for Sanitize.|
|bind_pdf(src_doc)|Initializes the facade.|
|save(output_file)|Saves the result PDF to file.|
|save(output_stream)|Saves the result PDF to stream.|
|close()|Closes the facade.|
|recover()|Recovers document.<br/>            Use properties to customize.|
|trim_top()|Removes data before %PDF.|
|trim_bottom()|Removes data after last %%EOF.|
|rebuild_xref_and_trailer()|Removes old xref with trailer and creates a new xref with trailer.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

