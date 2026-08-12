---
title: "System::Text::RegularExpressions::Regex::IsMatch metod"
linktitle: "IsMatch"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Regex::IsMatch metod. Matchar regex mot sträng i C++."
type: docs
weight: 500
url: /sv/cpp/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method


Matchar regex mot sträng.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Målssträng. |
| startat | int | Startindex. |

### ReturnValue

Sant om strängen matchar regex, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method


Kontrollerar om strängen matchar mönstret.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | const String\& | Indata-sträng. |
| mönster | const String\& | Regexp-mönster. |
| options | RegexOptions | Matchningsalternativ. |
| matchTimeout | TimeSpan | Timeout. |
| startat | int | [Match](../../match/) startposition. |

### ReturnValue

Sant om en träff hittas, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Enum [RegexOptions](../../regexoptions/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.PDF for C++](../../../)
