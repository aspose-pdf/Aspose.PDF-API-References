---
title: Aspose::Pdf::Text::MarkupParagraph class
linktitle: MarkupParagraph
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::MarkupParagraph class. Represents a paragraph in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class


Represents a paragraph.

```cpp
class MarkupParagraph : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ContinuationPageNumbers](./get_continuationpagenumbers/)() const | List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page. |
| [get_Fragments](./get_fragments/)() | [Collection](../../aspose.pdf/collection/) of not empty [TextFragment](../textfragment/) objects of the paragraph. |
| [get_Lines](./get_lines/)() const | Lines of paragraph. Each line represented by list of text fragments. |
| [get_Points](./get_points/)() | Points of polygon that describes paragraph. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [get_SecondaryPoints](./get_secondarypoints/)() const | Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [get_Text](./get_text/)() | Gets the paragraph text. |
| [set_Text](./set_text/)(System::String) | Sets the paragraph text. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
