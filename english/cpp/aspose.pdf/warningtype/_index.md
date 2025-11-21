---
title: Aspose::Pdf::WarningType enum
linktitle: WarningType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::WarningType enum. Enum represented warning type in C++.'
type: docs
weight: 27000
url: /cpp/aspose.pdf/warningtype/
---
## WarningType enum


Enum represented warning type.

```cpp
enum class WarningType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| SourceFileCorruption | 0 | The file is corrupted. |
| DataLoss | 1 | Text/chart/image or other data is completely missing from either the documet tree following load, or the created document following save. |
| MajorFormattingLoss | 2 | Major formatting losses compared to the original document. This is for occasions when the formatting loss is substantial but the data is still there. |
| MinorFormattingLoss | 3 | Minor formatting losses compared to the original document. This is for minor losses of fidelity. |
| CompatibilityIssue | 4 | Known issue that will prevent the document being opened by certain user agents, or previous versions of user agents. |
| InvalidInputStreamType | 5 | Invalid input stream type. |
| UnexpectedContent | 99 | The file has unexpected content. |

## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
