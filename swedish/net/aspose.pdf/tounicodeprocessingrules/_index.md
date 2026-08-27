---
title: "Klass ToUnicodeProcessingRules"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ToUnicodeProcessingRules-klass. Denna klass beskriver regler som kan användas för att lösa Adobe Preflight-felet Text kan inte mappas till Unicode"
type: docs
weight: 11300
url: /sv/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Denna klass beskriver regler som kan användas för att lösa Adobe Preflight‑felet \"Text kan inte mappas till Unicode\".

```csharp
public class ToUnicodeProcessingRules
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initierar en ny instans av klassen `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initierar en ny instans av klassen `ToUnicodeProcessingRules` med det angivna alternativet för att ta bort mellanslag från CMap-namn. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initierar en ny instans av klassen `ToUnicodeProcessingRules` med angivna alternativ. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger felet "Text cannot be mapped to Unicode". Använd detta flagga för att mappa icke‑länkade symboler till Unicode‑"space" (kod 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Vissa teckensnitt har ToUnicode-teckenkodkartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Detta flagga instruerar att ta bort mellanslag från namn på ToUnicode‑teckenkodkartor. Standardvärdet är falskt. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


