---
title: System::Globalization::CompareOptions enum
linktitle: CompareOptions
second_title: Aspose.PDF for C++ API Reference
description: 'System::Globalization::CompareOptions enum. String comparison options in C++.'
type: docs
weight: 3300
url: /cpp/system.globalization/compareoptions/
---
## CompareOptions enum


[String](../../system/string/) comparison options.

```cpp
enum class CompareOptions : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No special options. |
| IgnoreCase | 1 | Ignore case. |
| IgnoreNonSpace | 2 | Ignore nonspacing combining characters, e. g. diacritics. |
| IgnoreSymbols | 4 | Include whitespaces, punctuation signs and so on. |
| IgnoreKanaType | 8 | Ignore kana type (Japanese). |
| IgnoreWidth | 16 | Ignore character width wen comparing strings. |
| OrdinalIgnoreCase | 268435456 | Ordinal comparison with case difference ignored. |
| StringSort | 536870912 | Use string sort algorithm to compare characters. |
| Ordinal | 1073741824 | Compare UTF codes directly for first comparison. |

## See Also

* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
