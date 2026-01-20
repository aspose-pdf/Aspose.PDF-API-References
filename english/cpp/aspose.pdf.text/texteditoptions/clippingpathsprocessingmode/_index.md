---
title: Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum
linktitle: ClippingPathsProcessingMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum. Clipping path processing modes in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.text/texteditoptions/clippingpathsprocessingmode/
---
## ClippingPathsProcessingMode enum


Clipping path processing modes.

```cpp
enum class ClippingPathsProcessingMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| KeepIntact | 0 | Keeps clipping paths of the original page layout. (Default) |
| Expand | 1 | Original clipping path will be expanded in the case edited text requires more space. |
| Remove | 2 | Original clipping path will be removed in the case edited text requires more space. Caution: Because of clipping paths may interact with each other removing of it may lead to unexpected result on the page layout. |

## See Also

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
