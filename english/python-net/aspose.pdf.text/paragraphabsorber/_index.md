---
title: ParagraphAbsorber
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents an absorber object of page structure objects such as sections and paragraphs.<br/>            Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. <br/>            Also performs text segments search and provides access to search results via TextFragments collections grouped by structure elements.
type: docs
weight: 240
url: /python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Represents an absorber object of page structure objects such as sections and paragraphs.<br/>            Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. <br/>            Also performs text segments search and provides access to search results via TextFragments collections grouped by structure elements.

The ParagraphAbsorber type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ParagraphAbsorber()|Initializes a new instance of the [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) that performs search for sections/paragraphs of the document or page.|
|ParagraphAbsorber(sections_search_depth)|Initializes a new instance of the ParagraphAbsorber class|
## Properties
| Name | Description |
| :- | :- |
|page_markups|Gets collection of [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) that were absorbed.|
|sections_search_depth|Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed.<br/>            Default search depth is 3.<br/>            It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).|
|is_multicolumn_paragraphs_allowed|Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section.|
## Methods
| Name | Description |
| :- | :- |
|visit(doc)|Performs search for sections and paragraphs on the specified [Document](/pdf/python-net/aspose.pdf/document/).|
|visit(page)|Performs search on the specified [Page](/pdf/python-net/aspose.pdf/page/).|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

