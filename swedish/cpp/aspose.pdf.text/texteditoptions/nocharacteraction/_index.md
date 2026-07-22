---
title: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum"
linktitle: "NoCharacterAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum. Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.text/texteditoptions/nocharacteraction/
---
## NoCharacterAction enum


Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet.

```cpp
enum class NoCharacterAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ThrowException | 0 | Kasta undantag. |
| UseStandardFont | 1 | Ersätt teckensnitt med standardteckensnitt som innehåller det nödvändiga tecknet. |
| ReplaceAnyway | 2 | Ersätt text ändå utan teckensnittssubstitution. |
| ReplaceFonts | 3 | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittssubstitutionsalgoritmen följer dessa steg: |
| UseCustomReplacementFont | 4 | Ersätt teckensnitt till definierat ersättningsteckensnitt. |

## Se även

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
