---
title: System::Text::RegularExpressions::Regex::IsMatch method
linktitle: IsMatch
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex::IsMatch method. Matches regex against string in C++.'
type: docs
weight: 500
url: /cpp/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method


Matches regex against string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Target string. |
| startat | int | Beginning index. |

### ReturnValue

True if string matches regex, false otherwise.

## See Also

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method


Checks if string matches pattern.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| options | RegexOptions | Matching options. |
| matchTimeout | TimeSpan | Timeout. |
| startat | int | [Match](../../match/) beginning position. |

### ReturnValue

True if match is found, false otherwise.

## See Also

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
