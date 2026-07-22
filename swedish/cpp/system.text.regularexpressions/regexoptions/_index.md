---
title: "System::Text::RegularExpressions::RegexOptions enum"
linktitle: "RegexOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::RegexOptions enum. Regex-alternativ i C++."
type: docs
weight: 900
url: /sv/cpp/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) options.

```cpp
enum class RegexOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Standardbeteende. |
| Kompilerad | 1 | Kompilera regex för prestanda. Alltid gjort som standard. |
| CultureInvariant | 2 | Använd kulturinvariant matchning. Ignorerad. |
| ECMAScript | 4 | Använd ECMAScript-syntax. Ignorerad. |
| ExplicitCapture | 8 | Endast explicit fångst. Ignorerad. |
| IgnoreCase | 16 | Ignorera skiftläge vid matchning. |
| IgnorePatternWhitespace | 32 | Ignorera blanksteg i mönster. Stöds inte. |
| Multiline | 64 | Behandla '^' och '$' som början och slut på rad, inte hela strängen. |
| RightToLeft | 128 | Matchning från höger till vänster. Stöds inte. |
| Singleline | 256 | Gör så att '.' matchar vilket tecken som helst utan undantag (normalt matchas inte radbrytningstecken). |

## Se även

* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
