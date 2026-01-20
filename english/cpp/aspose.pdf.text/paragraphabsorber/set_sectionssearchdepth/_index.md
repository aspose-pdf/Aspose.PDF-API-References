---
title: Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth method
linktitle: set_SectionsSearchDepth
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth method. Sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns) in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.text/paragraphabsorber/set_sectionssearchdepth/
---
## ParagraphAbsorber::set_SectionsSearchDepth method


Sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns).

```cpp
void Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth(int32_t value)
```

## Remarks


Increasing of this value may lead to minor decreasing performance with no visible changes in search result. Decreasing of this value may lead to incorrect determination of paragraphs in sections. We are not recommend to set value less than default if you aren't desire to get only 'rough' elements of page structure. 
## See Also

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
