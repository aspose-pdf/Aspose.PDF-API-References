---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Aspose.PDF för .NET API‑referens"
description: "RenderingOptions property. Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg 1. Om användaren explicit anger DefaultFontName‑egenskapen, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök genom teckensnitt som lagts till via FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reservsökning, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen."
type: docs
weight: 20
url: /sv/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via !:FontRepository.Sources. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Se även

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


