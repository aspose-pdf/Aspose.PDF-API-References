---
title: Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum
linktitle: FontEncodingRules
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::FontEncodingRules enum. This enumeration defines rules which tune encoding logic in C++.'
type: docs
weight: 5200
url: /cpp/aspose.pdf/htmlsaveoptions/fontencodingrules/
---
## FontEncodingRules enum


This enumeration defines rules which tune encoding logic.

```cpp
enum class FontEncodingRules : uint8_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Leave encoding logic "as is" - in accordance with PDF specification. |
| DecreaseToUnicodePriorityLevel | 1 | ToUnicode is a special mechanism which helps to decode input codes to unicode symbols. According to specification it must be used first of all mechanisms to get unicode symbols for specific input code. But some documents has non-standard fonts and to convert these documents correctly it may be necessary to decrease ToUnicode priority and use another mechanisms to decode input codes. |

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
