---
title: "Aspose::Pdf::Text::TextRenderingMode enum"
linktitle: "TextRenderingMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextRenderingMode enum. Textrenderingsläget, Tmode, bestämmer om visning av text ska orsaka att glyfkonturer streckas, fylls, används som en beskärningsgräns, eller någon kombination av de tre i C++."
type: docs
weight: 6100
url: /sv/cpp/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enum


Textrenderingsläget, Tmode, bestämmer om visning av text ska göra att glyfkonturer streckas, fylls, används som en beskärningsgräns, eller någon kombination av de tre.

```cpp
enum class TextRenderingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| FillText | 0 | Fyll text. |
| StrokeText | 1 | Streck text. |
| FillThenStrokeText | 2 | Fyll, sedan streck text. |
| Invisible | 3 | Varken fyll eller streck text (osynlig). |
| FillTextAndAddPathToClipping | 4 | Fyll text och lägg till i sökväg för beskärning (se 9.3.6, "Text Rendering Mode,"). |
| StrokeTextAndAddPathToClipping | 5 | Streck text och lägg till i sökväg för beskärning. |
| FillThenStrokeTextAndAddPathToClipping | 6 | Fyll, sedan streck text och lägg till i sökväg för beskärning. |
| AddPathToClipping | 7 | Lägg till text i sökväg för beskärning. |

## Se även

* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
