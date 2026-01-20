---
title: System::Text::RegularExpressions::Regex::Match method
linktitle: Match
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex::Match method. Matches regex against string in C++.'
type: docs
weight: 600
url: /cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Matches regex against string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Target string. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## See Also

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, int, int) method


Matches regex against string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Target string. |
| startat | int | Beginning index. |
| length | int | Number of characters to look through (0 to look through the whole string). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## See Also

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Matches string and pattern.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| pattern | const String\& | Regexp pattern. |
| options | RegexOptions | Matching options. |
| matchTimeout | TimeSpan | Timeout. |
| startat | int | [Match](../../match/) beginning position. |
| length | int | Number of characters to look through (0 diables limit). |

### ReturnValue

First match found.

## See Also

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
