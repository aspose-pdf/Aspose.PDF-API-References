---
title: Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum
linktitle: TextFormattingMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextExtractionOptions::TextFormattingMode enum. Defines different modes which can be used while converting pdf document into text. See TextDevice class in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.text/textextractionoptions/textformattingmode/
---
## TextFormattingMode enum


Defines different modes which can be used while converting pdf document into text. See [TextDevice](../) class.

```cpp
enum class TextFormattingMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Pure | 0 | Represent pdf content with a bit of formatting routines. |
| Raw | 1 | Represent pdf content as is, i.e. without formatting. |
| Flatten | 2 | Represent pdf content with positioning text fragments by their coordinates. It is basically similar to "Raw" mode. But while "Raw" focuses on preserving the structure of text fragments (operators) in a document, "Flatten" focuses on keeping text in the order it is read. |
| MemorySaving | 3 | Extraction with memory saving. It is almost same to 'Raw' mode but works slightly faster and uses less memory. |

## See Also

* Class [TextExtractionOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
