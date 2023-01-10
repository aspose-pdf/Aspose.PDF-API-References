---
title: MarkupParagraph
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a paragraph.
type: docs
weight: 200
url: /python-net/aspose.pdf.text/markupparagraph/
---

## MarkupParagraph class

Represents a paragraph.

The MarkupParagraph type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|points|Points of polygon that describes paragraph.<br/>            Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.|
|secondary_points|Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page.<br/>            Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence.|
|continuation_page_numbers|List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page.|
|fragments|Collection of not empty [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) objects of the paragraph.|
|lines|Lines of paragraph. Each line represented by list of text fragments.|
|text|Gets string text object that the [MarkupParagraph](/pdf/python-net/aspose.pdf.text/markupparagraph/) object represents.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

