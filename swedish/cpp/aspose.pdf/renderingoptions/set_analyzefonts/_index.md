---
title: "Aspose::Pdf::RenderingOptions::set_AnalyzeFonts metod"
linktitle: "set_AnalyzeFonts"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::RenderingOptions::set_AnalyzeFonts metod. Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittsersättningsalgoritmen följer dessa steg: i C++."
type: docs
weight: 1700
url: /sv/cpp/aspose.pdf/renderingoptions/set_analyzefonts/
---
## RenderingOptions::set_AnalyzeFonts method


Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Teckensnittssubstitutionsalgoritmen följer dessa steg:

```cpp
void Aspose::Pdf::RenderingOptions::set_AnalyzeFonts(bool value)
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
