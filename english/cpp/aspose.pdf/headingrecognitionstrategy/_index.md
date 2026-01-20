---
title: Aspose::Pdf::HeadingRecognitionStrategy enum
linktitle: HeadingRecognitionStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HeadingRecognitionStrategy enum. Represents types of header recognition strategies in C++.'
type: docs
weight: 23900
url: /cpp/aspose.pdf/headingrecognitionstrategy/
---
## HeadingRecognitionStrategy enum


Represents types of header recognition strategies.

```cpp
enum class HeadingRecognitionStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Outlines | 0 | Represents the header recognition strategy by means of outlines. |
| Heuristic | 1 | Represents the header recognition strategy by means of heuristics rules and font size statistic. |
| Auto | 2 | Provides an automatic header recognition strategy selection. This is the default option. If the document contains bookmarks, the [Outlines](../outlines/) strategy will be selected, otherwise [Heuristic](./) |
| None | 3 | Do not recognize headers. This option can be useful in complexly formatted documents. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
