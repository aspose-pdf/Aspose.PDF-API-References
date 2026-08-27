---
title: "Enum TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet"
type: docs
weight: 11040
url: /sv/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Åtgärd att utföra om teckensnittet inte innehåller det nödvändiga tecknet

```csharp
public enum NoCharacterAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ThrowException | `0` | Kasta undantag |
| UseStandardFont | `1` | Ersätt teckensnitt till standardteckensnitt som innehåller det nödvändiga tecknet |
| ReplaceAnyway | `2` | Ersätt text ändå utan teckensnittssubstitution |
| ReplaceFonts | `3` | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Algoritmen för teckensnittssubstitution följer dessa steg: 1. Om användaren explicit anger Font‑egenskapen, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via [`Sources`](../fontrepository/sources/). 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reservlösning, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen. |
| UseCustomReplacementFont | `4` | Ersätt teckensnitt till definierat ersättningsteckensnitt. |

### Se även

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


