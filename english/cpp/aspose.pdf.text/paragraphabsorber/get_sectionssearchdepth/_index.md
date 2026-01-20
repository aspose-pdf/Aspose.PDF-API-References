---
title: Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth method
linktitle: get_SectionsSearchDepth
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth method. Gets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns) in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.text/paragraphabsorber/get_sectionssearchdepth/
---
## ParagraphAbsorber::get_SectionsSearchDepth method


Gets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).

```cpp
int32_t Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth() const
```

## Remarks


Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure. 
## See Also

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
