---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. Åtgärd att utföra om teckensnittet inte innehåller det nödvändiga tecknet
type: docs
weight: 10860
url: /sv/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction uppräkning

Åtgärd att utföra om teckensnittet inte innehåller det nödvändiga tecknet

```csharp
public enum NoCharacterAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ThrowException | `0` | Kasta undantag |
| UseStandardFont | `1` | Ersätt teckensnitt med standardteckensnitt som innehåller det nödvändiga tecknet |
| ReplaceAnyway | `2` | Ersätt text ändå utan teckensnittsbyte |
| ReplaceFonts | `3` | Ersätter teckensnitt efter behov för att säkerställa att alla tecken i texten kan visas. Algoritmen för teckensnittsbyte följer dessa steg: 1. Om användaren uttryckligen ställer in egenskapen Font, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är inställt, sök igenom teckensnitt som lagts till via [`Sources`](../fontrepository/sources/). 3. Analysera texten för att identifiera dess alfabet eller skrift och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en fallback, sök i systemet efter något teckensnitt som kan visa de nödvändiga tecknen. |
| UseCustomReplacementFont | `4` | Ersätt teckensnitt med definierat ersättningsteckensnitt |

### Se Även

* klass [TextEditOptions](../texteditoptions/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../)