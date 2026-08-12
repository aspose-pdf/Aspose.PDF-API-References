---
title: "Aspose::Pdf::RenderingOptions::get_AnalyzeFonts metod"
linktitle: "get_AnalyzeFonts"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::RenderingOptions::get_AnalyzeFonts metod. Ersätter fonter vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf/renderingoptions/get_analyzefonts/
---
## RenderingOptions::get_AnalyzeFonts method


Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittssubstitutionsalgoritmen följer dessa steg:

```cpp
bool Aspose::Pdf::RenderingOptions::get_AnalyzeFonts() const
```

## Anmärkningar


1. Om användaren uttryckligen anger egenskapen DefaultFontName, kontrollera om den angivna fonten kan visa de önskade tecknen.
1. Om ingen användardefinierad font är angiven, sök igenom fonter som lagts till via [FontRepository::Sources](../).
1. Analysera texten för att identifiera dess alfabet eller skript och föreslå fonternamn därefter. Försök att hitta och använda dessa fonter från systemet.
1. Som en reserv, sök i systemet efter någon font som kan visa de erforderliga tecknen.


## Se även

* Class [RenderingOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
