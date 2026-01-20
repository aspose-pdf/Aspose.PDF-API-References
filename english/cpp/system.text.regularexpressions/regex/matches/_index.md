---
title: System::Text::RegularExpressions::Regex::Matches method
linktitle: Matches
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::RegularExpressions::Regex::Matches method. Gets all matches of regex in given string by matching repeatedly in C++.'
type: docs
weight: 700
url: /cpp/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method


Gets all matches of regex in given string by matching repeatedly.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const String\& | Input string. |
| startat | int | Index to start matching at. |

### ReturnValue

Collection of all matches found.

## See Also

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Gets all matches between string and pattern.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
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

All matches found by matching repeatedly.

## See Also

* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
