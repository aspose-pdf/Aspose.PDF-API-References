---
title: "System::Text::RegularExpressions::Regex::Match metod"
linktitle: "Match"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Regex::Match metod. Matchar regex mot sträng i C++."
type: docs
weight: 600
url: /sv/cpp/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method


Matchar regex mot sträng.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Målssträng. |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Se även

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, int, int) method


Matchar regex mot sträng.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Målssträng. |
| startat | int | Startindex. |
| längd | int | Antal tecken att gå igenom (0 för att gå igenom hela strängen). |

### ReturnValue

[Match](../../match/) value containing match status and submatches.

## Se även

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method


Matchar sträng och mönster.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| options | RegexOptions | Matchningsalternativ. |
| matchTimeout | TimeSpan | Timeout. |
| startat | int | [Match](../../match/) startposition. |
| längd | int | Antal tecken att gå igenom (0 inaktiverar gränsen). |

### ReturnValue

Första matchning hittad.

## Se även

* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
