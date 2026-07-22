---
title: "Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enum"
linktitle: "ReplaceAdjustment"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextReplaceOptions::ReplaceAdjustment enum. Bestämmer åtgärden som ska utföras efter ersättning av textfragment till kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan stycke rader för att behålla styckets högra kant; ShiftRestOfLine - förskjuter resten av raden enligt förändrad textlängd, radens längd kan ändras; Standardvärdet är ShiftRestOfLine i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.pdf.text/textreplaceoptions/replaceadjustment/
---
## ReplaceAdjustment enum


Bestämmer åtgärden som ska utföras efter att en textfragment har ersatts med en kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan stycke rader för att behålla styckets högra kant; ShiftRestOfLine - förskjuter resten av raden enligt den förändrade textlängden, radens längd kan ändras; Standardvärdet är ShiftRestOfLine.

```cpp
enum class ReplaceAdjustment
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Ingen åtgärd, ersatt text kan överlappa resten av raden. |
| AdjustSpaceWidth | 1 | Försöker justera mellanslag mellan ord för att behålla radlängden. |
| WholeWordsHyphenation | 2 | Försöker fördela ord mellan styckesrader för att behålla styckets högra kant. |
| IsFormFillingMode | 4 | Försöker sprida orden i det tillgängliga vita utrymmet med hjälp av styckets bredd. Om texten överflödar kommer den att döljas. |
| ShiftRestOfLine | 8 | (Standard) Förskjuter resten av raden enligt förändrad textlängd, radens längd kan ändras |

## Se även

* Class [TextReplaceOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
