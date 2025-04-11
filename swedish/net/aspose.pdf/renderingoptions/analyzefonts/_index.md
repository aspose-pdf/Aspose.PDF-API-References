---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: RenderingOptions-egenskap. Ersätter typsnitt vid behov för att säkerställa att alla tecken i texten kan visas. Algoritmen för typsnittsbyte följer dessa steg: 1. Om användaren uttryckligen ställer in egenskapen DefaultFontName, kontrollera om det angivna typsnittet kan visa de önskade tecknen. 2. Om inget användardefinierat typsnitt är inställt, sök igenom typsnitt som lagts till via FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skrift och föreslå typsnittsnamn därefter. Försök att lokalisera och använda dessa typsnitt från systemet. 4. Som en fallback, sök i systemet efter något typsnitt som kan visa de nödvändiga tecknen.
type: docs
weight: 20
url: /sv/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts-egenskap

Ersätter typsnitt vid behov för att säkerställa att alla tecken i texten kan visas. Algoritmen för typsnittsbyte följer dessa steg: 1. Om användaren uttryckligen ställer in egenskapen DefaultFontName, kontrollera om det angivna typsnittet kan visa de önskade tecknen. 2. Om inget användardefinierat typsnitt är inställt, sök igenom typsnitt som lagts till via !:FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skrift och föreslå typsnittsnamn därefter. Försök att lokalisera och använda dessa typsnitt från systemet. 4. Som en fallback, sök i systemet efter något typsnitt som kan visa de nödvändiga tecknen.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Se Även

* klass [RenderingOptions](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)